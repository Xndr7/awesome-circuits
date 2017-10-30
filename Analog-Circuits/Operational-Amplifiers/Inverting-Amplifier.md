# Inverting Amplifier

The inverting amplifier is an opamp configuration that produces a negative voltage gain relative to the input voltage.

## Schematic
![Inverting Amplifier Configuration](https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Op-Amp_Inverting_Amplifier.svg/300px-Op-Amp_Inverting_Amplifier.svg.png)

The relationship between the input and output voltage is as follows:
Vout = -Rf/Rin * Vin

## Components

Rf and Rin can be any value resistor you wish. There are many different kinds of opamps available, the two most common being the LM741 Operational Amplifier and the LF353 Operational amplifier.

You can even generalize Rf and Rin to be impedances, using inductors and/or capacitors as seen in Uses.

Note that the LM741 is very cheap, but it is not ideal as the bias current is much larger than the LF353.

### Datasheets

[LM741](http://www.ti.com/lit/ds/symlink/lm741.pdf)
[LF353](http://www.ti.com/lit/ds/snosbh3f/snosbh3f.pdf)

## Uses

When a capacitor is added in parallel to Rf, an active low-pass filter is created.

![active-low-pass](http://www.electronics-tutorials.ws/filter/fil29.gif)

The gain-bandwidth product of the opamp is negligible in the active low-pass filter because the bandwidth of the opamp is usually much larger than the bandwidth of the filter. For very large passbands, the gain-bandwidth product of the opamp creates a second pole.

When a capacitor is added in series with Rf, an active high-pass filter is created.
![active-high-pass](http://www.electronics-tutorials.ws/filter/fil31.gif)

Note that when the gain-bandwidth product of the opamp is taken into consideration, the active high-pass filter is not a true high-pass filter, but a bandpass filter. The higher the gain-bandwidth product of the opamp, the larger the passband will be.


The inverting amplifier also has applications in signal processing and audio.

## Sources

https://en.wikipedia.org/wiki/Operational_amplifier_applications
http://www.electronics-tutorials.ws/filter/filter_6.html 
http://www.electronics-tutorials.ws/filter/filter_5.html
