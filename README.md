# Pololu Zumo32U4 exercises

Version: 2.0.0<br/>
Based on Pololu software and git repo, but reworked to run on PlatformIO.<br/>

## Summary

The Zumo 32U4 robot consists of the Zumo chassis, the Zumo 32U4 Main Board, and the Zumo 32U4 Front Sensor Array.  It has an integrated AVR ATmega32U4 microcontroller, motor drivers, encoders, proximity sensors, line sensors, buzzer, four buttons, LCD connector, LSM303D accelerometer, and L3GD20H gyro.  The user's guide for the Zumo 32U4 robot is here:

https://www.pololu.com/docs/0J63

Note: Sumo rules dictate that the robot field is black with white borders. The code in our exercise has been modified to supported an inverted field aswell (white with black borders).

## Setup

Install VS Code: https://code.visualstudio.com/download

And then add the PlatformIO-extension: https://platformio.org/install/ide?install=vscode

![change lesson before upload](hints/vscodehint.png?raw=true)

## Exercises

Clone this repo and solve the lessons provided. By solving all lessons you will be able to put together the bare minimums to qualify for a Sumo match.

Try to solve the lessons only using the documentation provided here: https://pololu.github.io/zumo-32u4-arduino-library/

## Sumo matches

- Each match consists of 3 rounds, each lasting a maximum of 90 seconds.

- Robot that wins most rounds wins the match.

- The match loser is disqualified from the tournament.

- If the case of an undecided match, sudden death rules apply.

- Robots will start facing outwards! NOT towards each other.

- Deliberate damage to Robots will result in disqualification.

- It is not permitted to make any changes to the physical properties of the robots.

- The Game Masters decision is final.

- No changes to the Robot’s can be made during a match.

- Robots will delivered to the Game Master before each Match.

- The Game Master will activate both Robots simultaneously at the start of each Round.

- Robots must be activated by pressing the ‘B’ button. At this point the Robot must make a single “beep” sound and then wait 5 seconds before moving: <b>Failure to do both of these will result in the robot forfeiting the round.</b>

