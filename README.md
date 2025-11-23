
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter module takes the input signal in electrical form and then transforms it into optical (light) energy containing the same information. The optical fiber is the medium which takes the energy to the receiver. At the receiver light is converted back into electrical form with the same pattern as originally fed to the transmitter.

TRANSMITTER:

LED, digital DC coupled transmitters are one of the most popular varieties due to their ease of fabrication. We have used a standard TTL gate to drive a NPN transistor, which modulates the LED SFH450V or SFH 756V source. (Turns it on and off).

RECEIVER:

SFH-551V is a digital optodetector. It delivers a digital output, which can be processed directly with little additional external circuitry. The integrated circuit inside the SFH551V optodetector comprises the photodiode device, a transimpedance amplifier, a comparator and a level shifter.

The photodiode converts the detected light into a photocurrent. With the aid of an integrated lens the light emanating from the plastic Fiber is almost entirely focused on the surface of the diode. At the next stage the trans-impedance amplifier converts the photocurrent into a voltage. In the comparator, the voltage is compared to a reference voltage. In over to ensure good synchronism between the reference and the trans- impedance output voltage, the former is derived from a second circuit of a similar kind, which incorporates a “blind” photodiode. The comparator derives a level shifter with an open collector output stages. Here a catch diode (similar to Schottky-TTL) prevents the saturation of the output transistor, thus limiting the output voltage to the supply voltage.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).
<img width="646" height="234" alt="image" src="https://github.com/user-attachments/assets/94d808be-6a06-4454-9976-3ce0a5eebf68" />
Connect the output post OUT of Digital Buffer to the post TX IN of Transmitter.
Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
Connect the other end of the Fiber to detector SFH551V (Photo Transistor Detector) very carefully.
Observe the detected signal at post TTL OUT on oscilloscope.
<img width="652" height="236" alt="image" src="https://github.com/user-attachments/assets/f900ecf4-dc51-4db4-84c6-426110a0b726" />
To measure the digital bandwidth of the phototransistor vary the input signal frequency and observe the detected signal at various frequencies.
Determine the frequency at which the detector stops recovering the signal. This determines the max. bit rate on the digital link.
Keep switch SW9 towards TX2 position.
Keep Jumper JP7 towards +5V position.
Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
Observe the detected signal at post TTL OUT on oscilloscope.
<img width="671" height="243" alt="image" src="https://github.com/user-attachments/assets/2d1f3178-32bb-4966-96e1-3c5419495b17" />





---


## BLOCK DIAGRAM

<img width="889" height="520" alt="image" src="https://github.com/user-attachments/assets/a20c628c-ca06-4fc5-b44e-253bd7272006" />


---

## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-17 at 23 13 03_20fdafe2](https://github.com/user-attachments/assets/dfd56e88-afdd-4343-a229-ab09c26d3f82)

---

## MODEL GRAPH

<img width="964" height="434" alt="image" src="https://github.com/user-attachments/assets/f4641f6a-6e05-433a-bae4-4109fa00ae65" />

---

## GRAPH

![WhatsApp Image 2025-11-23 at 21 51 40_ca6b2bef](https://github.com/user-attachments/assets/d6920499-9d9c-4fb2-91c2-b8dab9bdd245)


---

## RESULT

The frequency response of phototransister detector in the 600nm and 950nm fiber digital link was stuided and the retain between input and received signal was verified.
