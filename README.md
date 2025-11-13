# SSB-SC-AM-MODULATOR-AND-DEMODULATOR
## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics
## EQUIPMENTS REQUIRED

•	Computer with i3 Processor

•	SCI LAB

Note: Keep all the switch faults in off position

## ALGORITHM
  1.	Define Parameters:
     
    •	Fs: Sampling frequency.
    •	T: Duration of the signal.
    •	Fc: Carrier frequency.
    •	Fm: Frequency of the message signal.
    •	Amplitude: Maximum amplitude of the message signal.
    
  2.	Generate Signals:
     
    •	Message Signal: The baseband signal that will be modulated.
    •	Carrier Signal: A high-frequency signal used for modulation.
    •	Analytic Signal: Constructed using the Hilbert transform to get the in-phase and quadrature components.

  3.	SSBSC Modulation:
     
    •	Modulated Signal: Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

  4.	SSBSC Demodulation:
     
    •	Mixing: Multiply the SSBSC signal with the carrier to retrieve the message signal.
    •	Low-pass Filtering: Apply a low-pass filter to remove high-frequency components and recover the original message signal.

  5.	Visualization:
     
    Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

## PROCEDURE

  •	Refer Algorithms and write code for the experiment.
  
  •	Open SCILAB in System
  
  •	Type your code in New Editor
  
  •	Save the file
   
  •	Execute the code
  
  •	If any Error, correct it in code and execute again
  
  •	Verify the generated waveform using Tabulation and Model Waveform
## MODEL GRAPH
<img width="747" height="338" alt="image" src="https://github.com/user-attachments/assets/dd117c5d-ee32-47c7-946c-df6180b0d33f" />

## PROGRAM

<img width="689" height="832" alt="Screenshot 2025-08-21 155459" src="https://github.com/user-attachments/assets/e3c77451-85ab-4e40-8aff-17e787a32b80" />

<img width="729" height="660" alt="Screenshot 2025-08-21 155532" src="https://github.com/user-attachments/assets/d3193c32-4879-4e03-a34b-e256a2a3cd68" />



## TABULATION

![IMG-20251016-WA0021](https://github.com/user-attachments/assets/079971ad-bb06-4426-977b-3acaece4f58e)


## OUTPUT

<img width="798" height="618" alt="image" src="https://github.com/user-attachments/assets/9e25008e-ed86-4ea5-b639-1cd19a859571" />


## RESULT

Thus, the SSB-SC-AM Modulation and Demodulation is experimentally done and the output is verified.


