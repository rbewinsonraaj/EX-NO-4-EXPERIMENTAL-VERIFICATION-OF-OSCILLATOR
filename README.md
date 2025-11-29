# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
<img width="1031" height="937" alt="image" src="https://github.com/user-attachments/assets/95ee6d7b-1b3c-459d-88bc-43d41558bb78" />



---

## MODEL GRAPH
![WhatsApp Image 2025-11-29 at 10 39 32_ba1b98a1](https://github.com/user-attachments/assets/e3556c74-adda-4900-8845-c8bc03fb5b5f)

## DESIGN
<img width="1389" height="553" alt="image" src="https://github.com/user-attachments/assets/af506a5c-82e2-433a-bbd6-e570e311968b" />

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

<img width="1334" height="347" alt="image" src="https://github.com/user-attachments/assets/6f470b73-2b56-42d5-9a48-6c151b756487" />

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 10 40 07_b01f7679](https://github.com/user-attachments/assets/35599443-7924-4b21-9568-9305dae8b7c3)


---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2025-11-29 at 10 40 55_1751cca2](https://github.com/user-attachments/assets/3e6b6f5d-47d9-44eb-8591-595a6552a22a)


---
## MODEL GRAPH
<img width="1462" height="766" alt="image" src="https://github.com/user-attachments/assets/cfc1dd26-a9ea-4179-8698-038c07f4837c" />

---

## DESIGN

<img width="1088" height="558" alt="image" src="https://github.com/user-attachments/assets/f9de1a36-3dfc-41c1-81c1-8aef3ce46971" />



---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION


<img width="1271" height="391" alt="image" src="https://github.com/user-attachments/assets/030446e7-4976-4b00-bbca-b017184c8873" />

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 10 41 57_e57c5506](https://github.com/user-attachments/assets/f97f7e74-5b95-4094-ad6b-70a9afede7b7)

## Result
![WhatsApp Image 2025-11-29 at 10 42 20_e594cf47](https://github.com/user-attachments/assets/5de90de9-631d-4177-9d61-a464a57df078)



