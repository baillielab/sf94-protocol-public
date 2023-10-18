---
title: Clinical protocol for measurement of lung oxygenation (S/F94)
numbersections: true
link-citations: true
reference-section-title: References
geometry: top=3cm, bottom=2.5cm, left=3cm, right=3cm
header-includes: |
    \sloppy
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhead[LO,LE]{S/F94 protocol}
    \fancyhead[CO,CE]{}
    \fancyfoot[CO,CE]{}
    \fancyfoot[LE,RO]{\thepage}
figureTitle: Figure
tableTitle: Table
figPrefix: Figure
eqnPrefix: Equation
tblPrefix: Table
urlcolor: teal
linkcolor: blue
citecolor: blue
---

<!--
	K Baillie, Fiona Mc, Neil Y, Mark, Roger,
-->


# The S/F94 clinical outcome measure {.unnumbered}

This is a protocol for measurement of lung oxygenation function as an outcome measure for a clinical study. S/F ratio is a simple correction for the measured S~a~O~2~ to take into account how much oxygen the patient is receiving (F~I~O~2~). It is simply calculated as SpO2 divided by FIO2. But if the patient's S~a~O~2~ is high, S/F stops being an accurate reflection of lung oxygenation function. This is because, above 94%, the S~a~O~2~ value can't rise much, no matter how much oxygen the patient is receiving (@sec:rationale). S/F94 fixes this by turning down the oxygen until the patient's SaO2 is below 94%.

**S/F94** is the S/F ratio measured when the patient's S~a~O~2~ is below 94% on any oxygen therapy, or at any S~a~O~2~ at when they are breathing air.

# How to measure {.unnumbered #sec:criteria}

Essential conditions:

1. Oxygen therapy is giving a **measurable percentage of oxygen** (@sec:measurable).

2. Patient has been **resting, not talking, on the same oxygen therapy or at least 5 minutes** (@sec:resting).

3. Either **S~p~O~2~ is less than 94%**, or the patient is breathing air.

If these conditions are met:

4. Complete the Case Rerport Form to record S~a~O~2~, the mode of oxygen delivery, and the percentage of oxygen being delivered (F~I~O~2~).

5. Revert to original oxygen therapy once the measurement is complete.

# Exclusions {.unnumbered}

This protocol should not be used in patients undergoing treatment for acute brain injury or post-cardiac arrest.

![Flowchart for measurement of S/F94](img/flowchart/flowchart.auto.pdf)

\newpage

# Additional information and procedures

## Modes of oxygen delivery that give a measurable percentage of oxygen {#sec:measurable}

If the patient is not receiving a measurable percentage of oxygen, change to a different mode of oxygen therapy: @sec:changing.

| Acceptable oxygen modes        | Description                                                                                                                                                                                                     | FIO2 to record  |
| ----------------------- | ------------------------------------------- |:------------------:|
| Room air                       | S~p~O~2~ on air is always acceptable if the patient has been breathing air for at least 5 minutes.                                                                                                             | 21%                |
| Venturi Mask                   | Venturi masks have a changeable attachment on the oxygen inflow stating an oxygen percentage.                                                                                                                                          | 24%, 28%, 31%, 35%, 40%, 60% |
| Trauma mask $\pm$ nasal prongs | A trauma mask (one with a non-rebreathing bag) is often used, sometimes together with nasal prongs, to provide maximal oxygenation for a ward patient. If this can't be reduced safely, FIO2 should be recorded at 70% | 70%                |
| HFNO                           | High-flow nasal oxygen                                                                                                                                                                                          | 21-100%            |
| Humidified O~2~                | A high-flow humidified system providing a specified oxygen percentage                                                                                                                                           | 21-100%            |
| CPAP/NIV                       | Any kind of continuous positive airway pressure  or non-invasive respiratory support                                                                                                                            | 21-100%            |
| IPPV                           | Invasive positive pressure ventilation through an endotracheal tube or tracheostomy                                                                                                                             | 21-100%            |
| ECMO                           | Extra-corporeal membrane oxygenation                                                                                                                                                                            | ECMO               |

## Changing oxygen {#sec:changing}

If the patient is receiving oxygen by nasal prongs or any simple non-Venturi mask, change to an acceptable oxygen system as clinically appropriate. Some suggestions are below:

| Previous mode                     | S~p~O~2~  | Change to        |
|:--------------------------------- |:--------- | ---------------- |
| Nasal prongs less than 4l/min             | above 90% | Room air         |
| Nasal prongs less than 4l/min             | above 86% | Venturi mask 24% |
| Simple (Hudson) facemask less than 4l/min | above 90% | Room air         |
| Simple (Hudson) facemask less than 4l/min | above 86% | Venturi mask 28% |
| Other masks with flow up to 15l/min | above 90% | Venturi mask 40% |
| Other masks with flow up to 15l/min | above 86% | Venturi mask 60% |
| Other masks with flow at or above 15l/min | below 86% | Do not reduce O~2~. Record FIO2 as 70% |

## Reducing oxygen {#sec:reducing}

If the patient remains comfortable, S~a~O~2~ values as low as 80%, particularly for short periods (less than 20mins), are not thought to be harmful. The patient should be watched continuously for signs of distress after each change to oxygen therapy. Cyanosis (blue colouration of the lips) is normal in patients with SaO2 values in the range expected for this measurement.

If S~p~O~2~ is above 94%, reduce the F~I~O~2~ and monitor S~p~O~2~ continuously for 5 minutes.

| Previous F~I~O~2~ | S~p~O~2~  | Change to F~I~O~2~ |
|:----------------- |:--------- | ------------------ |
| 30% or less       | above 94% | Room air           |
| 40% or less       | above 94% | 28-30%             |
| 60% or less       | above 94% | 40%                |
| 80% or less       | above 94% | 60%                |
| 100% or less      | above 94% | 80%                |


If the patient becomes breathless, agitated or feels unwell after a change in oxygen therapy, immediately revert to the previous oxygen therapy.

## Resting {#sec:resting}

The patient should be supine in bed or in a chair. If they are in bed, the head of the bed should be tilted upwards at $\geq$ 30$^\circ$. The patient must not be talking or exercising during this time.

## Special considerations

### Delirium/dementia

If patients are agitated this measurement will be very difficult and so the requirement that the patient should be resting and not talking will have to be relaxed. As long as the other criteria are met (patient is receiving a measurable percentage of oxygen, and SpO2 is less than 94% or the patient is breathing air)

### Talking

Our experience is that many Covid patients are keen to talk when we first meet them. If they meet the 3 essential conditions (see above: [How to measure]), then a SpO2 measurement can be taken immediately after you introduce yourself. Otherwise, explain to the patient that talking may alter their oxygen levels and so they must remain calm and silent for 5mins.

### Proning

Patients who are being managed prone (either awake proning or on IPPV) should have S/F94 measurements taken during the supine periods as part of standard care.

## CRF elements

- Delivery mode
- S~a~O~2~
- F~I~O~2~
- HFNO flow rate
- PEEP (CPAP/NIV/IPPV)
- RR (as an alternative endpoint)

# Rationale {#sec:rationale}

The SaO2/FIO2 ratio (S/F) is a continuous index of lung oxygenation function and can be calculated without an arterial blood gas sample. It correlates well with the most widely-used measure of oxygenation - PaO2/FIO2 ratio (P/F).[@kwackevaluationspo2fio22018] S/F under steady state conditions in humans can range from around 0.5 (severe oxygenation defect) to 4.8 (perfect oxygenation function).

A major limitation of S/F is the ceiling effect: at high SaO2 values, SaO2 ceases to be dependent on lung oxygenation function, because the blood is close to maximally-oxygenated. A healthy patient with perfect lungs breathing 21% oxygen with SaO2=0.99 would have S/F = 4.7; but the same patient breathing 100% oxygen would have S/F = 0.99.

The S/F94 measurement removes these erroneous values, providing better agreement with a gold standard measure of oxygenation function (P/F ratio, @fig:synthetic_PF).

<div id="fig:synthetic_PF">

![All values](img/synthetic/PF_s1.00.png){#fig:spfa width=50%}\ ![SaO2 $\leq$ 94% or FIO2 = 21% only](img/synthetic/PF_s0.94.png){#fig:spfb width=50%}

Comparison of P/F and (a) S/F or (b) S/F94 in synthetic data generated using an computer model of gas exchange.[PMID: 31428882] Points are coloured according the SaO2 as shown in the colour scale.

</div>


## Glossary

S~a~O~2~: *S*aturation of *a*rterial blood with oxygen (*O~2~*).

S~p~O~2~: *S*aturation (measured by *p*ulse oximetry) of arterial blood with oxygen (*O~2~*).

F~I~O~2~: *F*raction (*I*nspired) of oxygen (*O~2~*).













