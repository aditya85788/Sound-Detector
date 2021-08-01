# Sound-Detector
This circuit called ‘Sound Detector’ is what detects vibrations  of the sound waves and amplifies it to be heard distinctly by human ears. 
The Circuit is designed on Proteus using Operational Amplifiers, Darlington pair of transistors and microphone
Sometimes due to lack of concentration and our ignorance, we are unable to hear anything around us. 
And, that could lead to unfortunate misfortunes which could have been avoided 
with appropriate precautions. This circuit called ‘Sound Detector’ is what detects vibrations 
of the sound waves and amplifies it to be heard distinctly by human ears

The circuit works using two op-amp 741. When the microphone detects sound vibrations, the 
vibrations are converted to electrical signals. This output is given to First Op-amp 
(IC741) and the signal undergoes amplification.
This amplified signal is then forwarded to second IC741 circuit, which acts as a comparator 
device. In this IC, the inverting pin is given a reference voltage Vref.
The output of this IC is provided as triggering input pulse to Darlington Pair Transistors (For 
Current Amplification). 
The output is connected to a buzzer and a LED. Buzzer produces a beeping sound and the 
LED Glows at the end of operations. 
The buzzer should be kept at place where people can hear, and the sensor should be kept 
at places that require continuous monitoring. To prevent noises from AC mains, battery 
supplies should be used.

Circuit Implementation Basically requires following major components:

• Condenser Microphone

• Two LM741 IC forming two individual circuits one for amplification and the other which acts as comparator.

• Darlington Pair Transistors

• Piezo Buzzer and LED

• Other passive components like Resistors, Varistors ,Capacitors and a Battery Source


# Useful References
How to add Microphone in Proetus?

https://www.etechnophiles.com/how-to-add-microphone-library-to-proteus-in-2018/
