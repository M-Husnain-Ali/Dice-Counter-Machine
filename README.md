# Dice Counter Project

## Overview

This project aims to design a circuit that efficiently counts the frequency of each number appearing on a thrown dice. The company producing the dice has already developed a mechanical equipment for throwing the dice and a dice counter to register each throw. However, they require a circuit to accurately count the occurrences of each number and display the results on LCD screens.

## Functionality

The circuit is designed to work seamlessly with the existing equipment. It takes inputs from the dice counter, which has five outputs - four to indicate the number appearing on the dice and one to signal the availability of a new sample. The circuit then processes this information to count the frequency of each number and displays the results on six LCD screens.

## Components Used

- 3 to 8 line Decoder: Utilized to decode the outputs from the dice counter and facilitate further processing.
- Six 4-bit Counters: These counters are employed to keep track of the occurrences of each number (1 to 6).
- Six Display ICs: Integrated Circuits responsible for driving the LCD screens and displaying the counted frequencies.
- NAND Gates: Used for logical operations to control the flow of data within the circuit.
- Binary Switches: Input devices allowing manual configuration and adjustment of certain parameters if needed.

## Circuit Design

The circuit comprises several interconnected components working together to achieve the desired functionality. The inputs from the dice counter are decoded using the 3 to 8 line Decoder, which provides appropriate signals to the counters. Each counter is dedicated to counting the occurrences of a specific number (1 to 6).

Upon receiving the signal indicating a new sample, the counters update their counts accordingly. The counted frequencies are then fed into the Display ICs, which drive the six LCD screens to visually represent the results.

## Output

The output of the circuit is displayed on six LCD screens, each indicating the frequency of a particular number (1 to 6) appearing on the thrown dice. The results are updated in real-time as new samples are processed.

## Usage

1. Ensure that the mechanical equipment for throwing the dice and the dice counter are properly set up and operational.
2. Connect the outputs of the dice counter to the inputs of the designed circuit.
3. Power on the circuit and the LCD screens.
4. Start throwing dice using the mechanical equipment.
5. Monitor the LCD screens to observe the frequency of each number appearing on the dice.

## Contributors

- Husnain Ali (https://github.com/M-Husnain-Ali)

## Contact Information

For inquiries or support, please contact the project maintainers:

- m.husnainali.work@gmail.com
