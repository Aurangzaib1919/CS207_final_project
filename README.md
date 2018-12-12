# CS207_final_project
this repository is for cs 207 final project 
 this is cs 207 final project repository
 i am not sure what i will make probably a piano or something
 will update it with the time and ideas
 
 
#Overview

Here's a simple to-assemble venture that truly packs a considerable measure of blinkenlight for the exertion: a little pocket-estimate music visualizer we call "Piccolo".

Set Piccolo alongside the television or a few speakers and you'll see the lights react to music and sound — least notes toward the left end of the diagram, most elevated notes toward the right.

In fact this would be known as a "range analyzer," however as this isn't an accuracy logical instrument, we're more happy with naming it a "visualizer." It's entirely for show.This halfway Arduino venture demonstrates an unmistakable movement from contribution to handling and after that yield in a bundle that is engaging and simple for psyches to get a handle on: music and lights. It's not extract or "science-y" except if you strip back the layers.

#wiring


On the off chance that utilizing the LED lattice out of the blue or we can put the led strip, we unequivocally suggest working through that full instructional exercise first. This will give you a chance to test and affirm that the Matrix is legitimately collected before proceeding onward to this further developed undertaking.

In the event that working with a breadboard as we appear beneath, bind push headers on to the amplifier breakout and LED network knapsack sheets (three sticks on the previous, four on the last mentioned). You can alternatively utilize 90 degree headers on the off chance that you'd like either segment to be situated holding up.

On account of the "smarts" of the LED framework rucksack, this entire task requires less than twelve associations add up to:

Interface the Arduino's 3.3V stick both to the mic amp VCC stick and the Arduino's AREF stick. We utilize one of the power rails on the breadboard to course 3.3 Volts to the two areas. The AREF association is imperative — don't neglect this!

Interface the Arduino 5V stick to the LED lattice + stick.

Interface Arduino GND stick to both the mic amp GND stick and the LED network – stick. You can utilize a breadboard control rail, or the Arduino has various GND pins accessible.

Interface Arduino simple stick 0 to the mic amp OUT stick.

Interface Arduino pins SDA and SCL to the lattice rucksack D (information) and C (clock) pins, individually. Prior Arduino sheets do exclude SDA and SCL pins — rather, utilize simple pins 4 and 5.

For a current "R3" Arduino board, (for example, the Arduino Leonardo or later Arduino Uno and Mega sheets), the wiring ought to look like this:


On the off chance that utilizing a "work of art" Arduino load up — an Arduino Uno form R1 or R2, Arduino Duemilanove or Diecimila (with 328P chip), the network information and clock lines ought to be associated with simple pins 4 and 5

Bit of cake!

You can control the Arduino from the USB association or utilizing a battery or power supply associated with the DC jack. The LED grid draws two or three hundred milliamps at most, so we can securely control it through the Arduino.

