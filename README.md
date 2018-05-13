NB: You might find useful the [sample proposal](http://github.com/zamfi/ucb-jacobs-creative-programming-electronics-spring-2018/blob/master/hw/sample-proposal.md) useful in completing this assignment!

# Circuit Twister

Circuit Twister is an interactive game, much like Twister, in which players learn about the necessary components for building certain basic circuits (i.e. LED, DC Motor, and Servo circuits). 

## Team

Cade Cahalan
Chelsey Campillo
Ethan Frazin
Jefrey Nacar
Bennett Shaeffer

## Summary

Here, write a paragraph or two describing what you built for your final project and what was challenging. 

Include a discussion how it will be interactive or responsive to the environment.

## Component Parts

All of the buttons were created using copper capacitive sensors, each consisting of a layer of foam sandwiched between two copper and wood sheets. When touching, the copper sheets complete a circuit, similar to a switch, and activate an Arduino program. In order to receive feedback from the buttons, we soldered a wire to each copper sheet: one for ground and the other for the digital pin. Additionally, for the digital pin wires, we soldered a 10K resistor and utilized the INPUT_PULLUP function so that Arduino could monitor the state of the button.

Copper Sheets (Input) -> Arduino serial monitor (Data) -> Led turns on (Output)

## Challenges

A brief discussion of what was hard, challenging, or unexpected about your project.

## Timeline

- Week 1: Write proposal
- Week 2a: Receive feedback and re-format project 
- Week 2b: Test best method for building the buttons (i.e. build a button using an FSR sensor and one with copper sheets)
- Week 3a: Build all 30 buttons and make sure they are working properly
- Week 3b: Design the game mat using Illustrator
- Week 4: Assemble the vinyl/canvas mat together 
- Week 5: Present!

## Completed Work

Photos and videos of your completed final project!

## References and links

**Include a link to your final showcase one-pager here in PDF format.**

Tutorials, comments, videos, magazine articles - anything you found that helps you understand your project.
