# Non-Inverting Amplifier

The non-inverting amplifier is an opamp configuration used to produce a positive gain relative to the input voltage. Unlike with the inverting amplifier, a non-inverting amplifier cannot have a fractional gain. 

## Schematic
![Non inverting config](https://upload.wikimedia.org/wikipedia/commons/4/44/Op-Amp_Non-Inverting_Amplifier.svg)

The relationship between the input and output voltage is as follows:
Vout = (1+(R2/R1)) * Vin

## Components

R1 and R2 can be any impedances you wish.  There are many different kinds of opamps available, the two most common being the LM741 Operational Amplifier and the LF353 Operational amplifier.

## Datasheets
[LM741](http://www.ti.com/lit/ds/symlink/lm741.pdf)
[LF353](http://www.ti.com/lit/ds/snosbh3f/snosbh3f.pdf)

## Uses
The non-inverting amplifier can be used in most applications where the inverting amplifier is used, including active low and high pass filters. Below are examples of active filters using non-inverting amplifiers.
![active-low](http://www.electronics-tutorials.ws/filter/fil20.gif)
![active-high](http://www.electronics-tutorials.ws/filter/fil30.gif)

## Sources
https://en.wikipedia.org/wiki/Operational_amplifier_applications
http://www.electronics-tutorials.ws/filter/filter_6.html 
http://www.electronics-tutorials.ws/filter/filter_5.html

