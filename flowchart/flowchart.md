
graph LR

    p[Nasal prongs]
    max["Maximal ward oxygen":<br>Flow rate 16lpm or more<br>Through trauma/non-rebreather mask<br>With or without nasal cannulae<br>Assume FIO2=70%]
    m[Any non-Venturi simple facemask]
    
    max --> record
    
    change{CHANGE<br>OXYGEN}
    
    a[Room air]
    v[Venturi Mask O2]
    hum[Humidified O2]
    h[HFNO]
    c[CPAP/NIV]
    i[IPPV]
    e[ECMO<br>Record FIO2=ECMO]
    
    p --> change
    m --> change
    change -->a
    change -->v
    
    wait1[Wait<br>5mins]
    wait2[Wait<br>5mins]
    s94a[SaO2 is<br>less than 94%]
    s94b[SaO2 is<br>less than 94%]
    record[Record SaO2,<br>oxygen mode,<br>and FIO2]

    a --> wait1
    wait1 --> check21
    wait2 --> s94b
    
    check21[FIO2=21%] --> record
        
    v --> s94a
    hum --> s94a
    h --> s94a
    c --> s94a
    i --> s94a
    s94a --yes--> wait2
    s94a --no-->reduce{REDUCE<br>OXYGEN}
    reduce-->s94a
    s94b --yes--> record

    e --> record
    
    subgraph Initial oxygen therapy
    p
    m
    max
    end

    subgraph 1 Measurable O2
    a
    v
    hum
    h
    c
    i
    e
    end
    
    subgraph 2 Resting 5mins
    wait1
    wait2
    end
    
    subgraph 3 Check
    check21
    s94b
    end
    
    subgraph 4 CRF
    record
    end
    
    classDef default fill:#bec3e8,stroke:#333,stroke-width:1px,text-align:center;
    classDef choices fill:#ffc6c6,stroke:#333,stroke-width:0px,font-weight:bold,text-align:center;
    class reduce,change choices


