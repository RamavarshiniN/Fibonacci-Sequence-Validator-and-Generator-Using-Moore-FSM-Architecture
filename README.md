# Fibonacci-Sequence-Validator-and-Generator-Using-Moore-FSM-Architecture
Design a Fibonacci sequence generator and validator using Moore FSM, where outputs depend only on states. The system generates Fibonacci numbers and verifies input sequences using state transitions.

# Problem Statement Description

This problem focuses on designing a Fibonacci Sequence Validator and Generator using the Moore Finite State Machine (FSM) architecture. The objective is to model the behavior of a system that generates Fibonacci numbers sequentially and validates whether a given input sequence follows the Fibonacci rule, where each number is the sum of the previous two numbers.

Using a Moore FSM, the system’s output depends only on the current state, ensuring stable and predictable outputs. The FSM transitions through states representing consecutive Fibonacci numbers, updating its state based on clock pulses. For validation, the FSM compares incoming inputs with expected Fibonacci values and indicates whether the sequence is valid.

This design demonstrates the application of sequential logic, state transitions, and clock-driven control in digital systems. It highlights how Moore machines can be effectively used to implement mathematical sequence generation and validation in hardware-oriented architectures.

# Overview

This project implements a Fibonacci Sequence Validator and Generator using the Moore Finite State Machine (FSM) architecture. The system generates Fibonacci numbers sequentially and validates whether a given input sequence follows the Fibonacci rule.

# 🎯 Objective

Generate Fibonacci numbers using state transitions

Validate an input sequence based on Fibonacci logic

Demonstrate Moore FSM behavior where outputs depend only on the current state

# ⚙️ Working Principle

In this design, each state of the Moore FSM represents a Fibonacci number. On every clock pulse, the FSM transitions to the next state based on predefined logic.
For validation, the input value is compared with the expected Fibonacci number of the current state. If it matches, the sequence is considered valid; otherwise, it is flagged as invalid.

# 🧠 Key Concepts Used

Moore Finite State Machine

Sequential Logic Circuits

State Transition Diagrams

Clock-driven digital systems

# 🚀 Applications

Sequence generation systems

Pattern validation circuits

Digital control and verification systems

Educational demonstration of FSM concepts

# 📁 Project Structure
src        → Source code  
hardware      → image of zedboard
output_sample_from_EDA     → image of output
README.md   → Project documentation  

# ✅ Conclusion

This project demonstrates how mathematical sequences like Fibonacci can be efficiently modeled using Moore FSM architecture, ensuring stable and predictable outputs in digital systems.
