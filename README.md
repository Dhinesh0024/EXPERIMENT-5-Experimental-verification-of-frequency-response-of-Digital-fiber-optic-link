
# Exp 5 Experimental verification of frequency response of Digital fiber optic link

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

<img width="504" height="208" alt="5" src="https://github.com/user-attachments/assets/d1fac656-ff64-4f0d-8449-4b5d32606e29" />


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

<img width="515" height="127" alt="55" src="https://github.com/user-attachments/assets/e79ead0b-2fa2-4e94-9f32-87613d748629" />


## TABULATION  
**Transmission through Digital Link**

![5555](https://github.com/user-attachments/assets/f72155db-de59-4081-a94e-c46dbd9b2883)


## MODEL GRAPH

<img width="599" height="322" alt="555" src="https://github.com/user-attachments/assets/865cf66e-f519-4479-947d-63dd35d51ba7" />

![WhatsApp Image 2025-11-18 at 10 56 08_36727bc6](https://github.com/user-attachments/assets/ad3be6f7-5c77-428f-be25-c4e438fedb29)


## RESULT

The digital 660 nm fiber optic link accurately reproduced the input square wave at the receiver, confirming proper digital signal transmission and bandwidth response.
