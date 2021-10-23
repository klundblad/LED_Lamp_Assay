## Basic PWM Circuit
<img width="601" alt="PWM LED Circuit" src="https://user-images.githubusercontent.com/12982852/138574318-18f6c8f5-ae88-487b-8f1e-12ce7910af86.PNG">

PWM stands for "Pulse Width Modulation", outputting a square wave in which the width of the wavelength can be adjusted by the resistance on the 
potentiometer. The 555 timer IC acts as a Comparator to output a desired current to the LED's. The hardware's current configuration
assumes a potentiometer will be outside of the field box to control externally while data is captured. The battery may also be external in order 
to limit the amount of tampering within the field box

## LED Output
Assuming the Pot is not limiting the input (VCC of the LM555 is receiving 9 V) <br />
I_(LED) = 19.284 mA (Green LEDs rated 20 mA) <br />
V_d(LED) = 1.848 V <br />

<img width="303" alt="PWMsimulated" src="https://user-images.githubusercontent.com/12982852/138574624-185e08ea-ca50-444c-ba2d-42dae5105879.PNG">
[Using Falsdad Online Circuits](https://www.falstad.com/circuit/)
