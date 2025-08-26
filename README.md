# AM-Transmitter-Module
This Module is intend to send RF  ( Radio Frequence) waves for short Distances by a Frequence of 1.5 Mhz 

# Description :
The Board Contain 4 Main Stages :
Audio Amplification through LM386.
A buffer Stage to isolate the oscillator from the Ic and amplify the current
Oscillator Stage through Colpitts Oscillator and a Crystal of 1.5 Mhz to produce the carrier Wave.
Modulation Stage with an Amplifier Class C ( Common Collector with an LC Tank ), to select the main Frequence and Amplify it.
PCB Design Though Altium ( 2 Layers are used, Poor Copper Grounded to Stabilise The Board from any Noise)

All Transistors are with Biasing to Maintain the Transistors in Active Region.
an RFC is intend to isolate the reflected AC Voltages from the Power Supply which is 10 Volt.
In Term of Resistances it is curcial to choose the Adequate Power to prevent any Heating and defection of The Circuit.
Coupling Capacitors Cancels the DC and permit to sound waves (AC) to Continue.
Decoupling small Capacitors permit to Smooth the Wave and reduce the Noise.
The LC Tank is Working is Resonance Mode  1 MHZ = 1/( 2 * pi * square (L * C)) To select the Main Frequence and send it to the Antenna.
The Class C Amplifier is Widely used in Term of RF, it consume smaller Power compare to  Class B and adaptable for better Amplification of RF with Smaller Noise.

# Oscillator Wave Frequence Through Multisim :


<img width="1160" height="544" alt="oscillator" src="https://github.com/user-attachments/assets/ca045b8e-adad-4e57-9b11-1beb1a634c17" />

# Output of The Modulator 




# A Matching Circuit is Needed For This Low Power RF Module
