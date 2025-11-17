
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

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

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

![WhatsApp Image 2025-11-17 at 23 18 26_ebff217f](https://github.com/user-attachments/assets/5df5d48c-bf6f-4b91-b11a-e1f89a878334)

---

## RESULT

The frequency response of phototransister detector in the 600nm and 950nm fiber digital link was stuided and the retain between input and received signal was verified.
