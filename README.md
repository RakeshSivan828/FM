# Frequency-Modulation

#EXP NO: 1	GENERATION AND DETECTION OF FM

AIM:

   To generate and detect the frequency modulation and demodulation u s i n g S C I L A B and to calculate modulation index of FM.

EQUIPMENTS REQUIRED

   •	Computer with i3 Processor

   •	SCI LAB

THEORY:

   Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.
FREQUENCY DEVIATION f and MODULATION INDEX m f :
   The frequency deviation f represents the maximum shift between the  modulatedsignal
 frequency, over and under the frequency of the carrier.

 We define modulation index m f the ratio between f and the modulating frequency
                    m= f / fm


FREQUENCY MODULATION GENERATION:
     The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.




Note: Keep all the switch faults in off position

Algorithm

 1.	Define Parameters:
   •	Fs: Sampling frequency.
   •	T: Duration of the signal.
   •	Fc: Carrier frequency.
   •	Fm: Frequency of the modulating signal.
   •	Beta: Modulation index, which controls the extent of frequency deviation.
 2.	Generate Signals:
   •	modulating_signal: Sinusoidal signal used for modulation.
   •	carrier_signal: The high-frequency carrier signal.
   •	modulated_signal: FM modulated signal calculated by varying the carrier frequency according to the modulating signal.
 3.	FM Modulation:
   •	Modulated_signal is obtained by modulating the carrier signal with the modulating signal.
 
 4.	FM Demodulation:
   •	Differentiation: Computes the derivative of the modulated signal to extract frequency variations.
   •	Envelope Detection: Takes the absolute value to retrieve the envelope of the signal.
   •	Low-pass Filtering: Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.
 5.	Visualization:
   •	Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.

PROCEDURE

  •	Refer Algorithms and write code for the experiment.
  •	Open SCILAB in System
  •	Type your code in New Editor
  •	Save the file
  •	Execute the code
  •	If any Error, correct it in code and execute again


Program

<img width="559" height="669" alt="image" src="https://github.com/user-attachments/assets/82c35b4f-1090-4a7e-ab4e-6b1a98f8a0b6" />

Output Waveform

<img width="1540" height="980" alt="image" src="https://github.com/user-attachments/assets/c5f80257-a004-4415-9ebc-3fff2c0e32fd" />


TABULATION:



Calculation
1.	ma (Theory) = am/ac =
2.	ma(Practical) = (Emax-Emin)/(Emax+Emin) =


MODEL GRAPH
 <img width="919" height="1290" alt="image" src="https://github.com/user-attachments/assets/58d5c50d-9a9e-4cab-a7b2-9c3ca2851ca8"/>

RESULT:
Thus the amplitude modulation and demodulation is experimentally done and the output is verified.
