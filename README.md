# gcd-machine

A GCD (Greatest Common Divisor) machine is a hardware device that computes the greatest common divisor of two numbers using datapath and control path components. Datapath refers to the collection of functional units and registers, while control path comprises the control logic responsible for coordinating the operations within the datapath. Here's a high-level description of a GCD machine using Verilog:

Datapath Components:

Two registers (A and B) to store the input numbers.
Comparators to compare the values in the registers.
A subtractor to perform subtraction operations.
A multiplexer to select the input for the subtractor.
A data output register to store the computed GCD value.
Control Path Components:

A finite-state machine (FSM) to control the overall operation of the GCD machine.
Control signals to enable/disable the datapath components based on the current state of the FSM.
Clock and reset signals to synchronize and initialize the system.
