# Requirements

## Introduction

* the name stands ASMD is arthamtic substraction multiplication division calculator

* The purpose of the project is to build a basic arthematic, substraction, multiplication, division calculator based on Atmega328 microcontroller. This ASMD calculator which can perform Signed operations on 64bits numbers with max of two different math symbols or any number of operands but with the same math symbol. It uses 4×4 matrix keyboard as input device. The result of calculation displayed on 16×2 LCD. 

* An LCD module can be interfaced with a microcontroller either in 8 bit mode or in 4 bit mode. This will saves the number of GPIO pins needed for other purpose.


## Components Used

1. AVR Atmega 328 Microcontroller
2. 4 Mhz Crystal Oscillator
3. 10 KΩ resistor
4. 22 pF capacitor
5. 4*4 Keypad Interface
6. 16*2 LCD Interface

## Software Used

1. SimulIDE
2. Visual Studio Code

## Cost and Feature

The ASMD has less expensive for build the system

A calculator is a device that performs numerical operations. The features of this basic calculator can perform 

1. Addition
2. Subtraction
3. Multiplication
4. Division

## SWOT Analysis

### Strength

1. The ultimate strength of calculators is its user-friendly and simple to use.

2. Calculators are long-lasting, and they have almost all kinds of basic ASMD operations.

### Weaknesses

1. The storage capacity is low to store the previous operations.
2. Anytime power supply is needed for the ASMD calculator to perform an operation.

### Opportunities

1. We can use a solar panel supply in ASMD calculators to reduce the power supply usage.

### Threats

1. Nowadays people are not intrested in buying electronic calculator becuase calculator operations are implemented in our portable accessories like smartphones and laptops etc.


## 4W's and 1H

### Why

1. To perform the basic numerical operations.
2. To reduce the manpower.

### Where

1. The calculator can be operated from anywhere.

### Who

1. Can be used by anyone for numerical operation

### When

1. Anyone who have to solve a basic calculation.

### How

1. Giving different inputs we can find their desired output.

## High Level Requirements
| ID | Description | Status |
|----|-------------|--------|
| HLR_1 | Control Unit | Implemented |
| HLR_2 | Input Unit | Implemented |
| HLR_3 | Output Unit | Implemented |
| HLR_4 | Software Design | Implemented |

## Low Level Requirements
| ID | Description | HLR ID | Status |
|----|-------------|--------|--------|
| LLR_1 | AVR Atmega 328 Microcontroller | HLR_1 | Implemented |    
| LLR_2 | 4*4 Keypad Interface | HLR_2 | Implemented |
| LLR_3 | 16*2 LCD Interface | HLR_3 | Implemented |
| LLR_4 | Visual Studio Code & Simulide | HLR_4 | Implemented |
