Overview

This project implements a 7-bit synchronous up counter using Cadence Virtuoso 45nm Technology. The counter starts from a preset value of 103, increments up to 127, then resets to 0 and counts up to 127 again. It incorporates T-flip flops, multiplexers, and control signals for sequence management.

Features

Preset Starting State: Begins counting from a calculated initial value based on student ID.

T-Flip Flop Based Design: Optimized for simplicity, efficiency, and reduced gate count.

Custom Counting Logic: Implements a control signal to toggle between counting sequences.

Low-Power CMOS Implementation: Designed using PMOS/NMOS transistors at 1.1V.

Cadence Virtuoso Simulation: Simulated and tested for functionality.

Design Components

Logic Gates: AND, OR, NAND, NOR, XOR, XNOR.

Multiplexer (2x1): Controls counting sequences.

T-Flip Flops: Store and toggle counter values.

Enable, Preset, and Reset Signals: Manage counter behavior.

System Functionality

Counter starts at 103, increments to 127, then resets to 0.

Control signal (Cs) changes state when the counter reaches 127.

Reset Signal ensures reinitialization to preset state.

Implementation

Technology: Cadence Virtuoso 45nm CMOS.

Clock Speed: Simulated at 100 MHz - 10 GHz.

Output Delay: Estimated across multiple configurations.

