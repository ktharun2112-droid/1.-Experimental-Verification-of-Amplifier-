#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-12-04 at 09 22 20_f67b8b7c](https://github.com/user-attachments/assets/1ce24eb9-6819-4667-a784-37f3bd446153)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-12-04 at 09 22 29_afdbb4a0](https://github.com/user-attachments/assets/15574216-9d70-4eaa-829c-d715cf90f18f)


MODEL GRAPH 

![WhatsApp Image 2025-12-04 at 09 23 00_d98a3a96](https://github.com/user-attachments/assets/0ef95501-7d26-4641-8c01-3b34d6f97622)



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2025-12-04 at 09 22 38_99458fa6](https://github.com/user-attachments/assets/749026ae-af03-4fd6-92fd-aee486c7a0ab)
		
 ![WhatsApp Image 2025-12-04 at 09 22 42_5dceeea2](https://github.com/user-attachments/assets/3e639c0e-acab-4f3f-bb8d-3d53cc15df57)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 09 27 57_90ae6bae](https://github.com/user-attachments/assets/22afa04d-fb8b-4fd0-b207-8704eac2f80b)

![WhatsApp Image 2025-12-04 at 09 28 35_3cedb12b](https://github.com/user-attachments/assets/ead153fd-2a54-49f6-bfdd-6bde9c3257b4)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-04 at 09 23 20_53b0f4e4](https://github.com/user-attachments/assets/23a99893-8c38-4ffb-9916-5692fdbf064c)



---

## MODEL GRAPH
![WhatsApp Image 2025-12-04 at 09 26 58_841ed3b9](https://github.com/user-attachments/assets/86491a43-8e8d-4171-ae03-1883853ccce0)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-12-04 at 09 23 27_08891cb6](https://github.com/user-attachments/assets/dbdbb225-f872-42f3-bdf5-d0a015fc1cd5)
![WhatsApp Image 2025-12-04 at 09 23 41_a01bdf35](https://github.com/user-attachments/assets/839e157f-f13c-4415-8d96-deada4d9d269)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 09 29 06_831e7207](https://github.com/user-attachments/assets/a8a6fa95-6a14-4a57-8ad8-42ac4a67a661)

![WhatsApp Image 2025-12-04 at 09 29 30_20feb32c](https://github.com/user-attachments/assets/968545bd-3f1f-45fd-bbae-f31d98c3b9d6)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-04 at 09 26 59_ee184433](https://github.com/user-attachments/assets/e00aef7e-28ed-446e-a7dc-6f2c3e0071d7)

## MODEL GRAPH
![WhatsApp Image 2025-12-04 at 09 26 59_d155bc9b](https://github.com/user-attachments/assets/d8e33244-0430-4201-b394-b0003e64ac01)

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-12-04 at 09 26 59_4c041599](https://github.com/user-attachments/assets/5d34fd48-f41f-4cf4-9fde-38d33fa54dc2)
![WhatsApp Image 2025-12-04 at 09 26 59_a222721a](https://github.com/user-attachments/assets/256718f1-3db3-4093-9667-d6a8b5b5ecfd)


---
## OUT PUT WAVEFORM AND DISCUSSION 


---![WhatsApp Image 2025-12-04 at 09 29 57_5d33acd4](https://github.com/user-attachments/assets/830bb177-8cd5-4bf0-b9b8-b86711bc32c3)

## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-12-04 at 10 01 05_898ede48](https://github.com/user-attachments/assets/3d63f8d2-9274-4651-b814-c1cb54e1fdf7)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-12-04 at 10 01 05_c1f08217](https://github.com/user-attachments/assets/4d08a9c4-44df-4672-8c19-f86f86d67e89)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 10 01 06_e2e31806](https://github.com/user-attachments/assets/913d27fc-1045-4ec2-a15c-8470c154d2da)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
