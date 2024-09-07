# sequnce_detector

Sequence Detector using Moore Machine
Overview
This project implements a sequence detector using a Moore state machine in Verilog. A sequence detector is a state machine that detects a specific sequence of bits from a stream of input. The output is asserted only when the entire sequence has been detected.

The sequence detector in this project is designed to detect a specific sequence (e.g., 1011). It utilizes a Moore state machine, where the output depends only on the current state, not on the input that caused the transition to that state.

Features:
Detects a specified binary sequence in a stream of input bits.
Implemented using a Moore state machine.
Outputs 1 when the sequence is detected, 0 otherwise.
Configurable for any binary sequence.

