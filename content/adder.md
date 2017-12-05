Title: Creating a 4-bit adder
Date: 2017-11-27 03:28
Modified: 2017-11-27 20:36
Category: Hardware
Tags: logic gates, breadboard
Slug: four-bit-adder
Status: Published
Author: Ethan Rogers
Summary: Writing about my experience wiring up a four bit adder

After discovering this video about creating an 8-bit computer out of some breadboards, wire and components, I have been researching the implementations of the abstractions of the different components, like the RAM, instruction register, program counter, etc.

I recently purchased my first electronic component kit I've had since I was a little kid. My plan was to use the included breadboard to create some logic gates using transistors, LEDs, and switches. I would then take the combination of logic gates to make a full adder with a carry bit, which would feed into the carry bit input of the next full adder, until I had four full adders combined to add two four bit binary numbers.

0 0 0 0
8 4 2 1

= 0

1 1 1 1
8 4 2 1

= 15

How many of each number is there?
One 1, one 2, one 4, one 8, added together is 15.