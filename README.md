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

Gaining inspiration from both the game Twister and this class, we decided to build an electronic version of Twister in order to make circuitry fun to learn. With each challenge, the team of players are to work together in pressing all of the buttons (each representing a specific circuit component) required to complete the challenge. As the game progresses, the challenges become more and more difficult, pushing users to think critically about the best method of completing the challenge. 

## Component Parts

All of the buttons were created using copper capacitive sensors, each consisting of a layer of foam sandwiched between two copper and wood sheets. When touching, the copper sheets complete a circuit, similar to a switch, and activate an Arduino program. In order to receive feedback from the buttons, we soldered a wire to each copper sheet: one for ground and the other for the digital pin. Additionally, for the digital pin wires, we soldered a 10K resistor and utilized the INPUT_PULLUP function so that Arduino could monitor the state of the button.

Copper Sheets (Input) -> Arduino serial monitor (Data) -> Led turns on (Output)

## Challenges

The most unexpected challenge we faced was gathering all of the data, from the 30 buttons we built, in a cohesive manner. Because we initially tried utlizing the resources we already had, specifically the arduinos and featherboards we already owned, we came across a problem in getting all of the arduinos (7 of them) to communicate accurately. After a series of debugging, and trial and error, we ended up purchasing Sparkfun's version of the Arduino Mega, which allowed us to hook up all of the buttons to a single microcontroller. 

## Timeline

- Week 1: Write proposal
- Week 2a: Receive feedback and re-format project 
- Week 2b: Test best method for building the buttons (i.e. build a button using an FSR sensor and one with copper sheets)
- Week 3a: Build all 30 buttons and make sure they are working properly
- Week 3b: Design the game mat using Illustrator
- Week 4: Assemble the vinyl/canvas mat together 
- Week 5: Present!

## Completed Work, References, and links

Link to Google Drive with Photos and Info Sheet: https://drive.google.com/open?id=1MqDm_zQpY6tGCz2yTiIk67k4bhceQTdw

Link to Arduino Mega code: https://github.com/bennettshaeffer/desinv23/blob/master/twister/mega/Mega_mat_feedback.ino 
