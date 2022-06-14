# A-MCX-Gate-in-CLIFFORD-Gate-Decomposition
I.INTRODUCTION

1.1 BACKGROUND

Many quantums operations include multi-controlled Toffoli(MCX) gates.
Among the most notable are Grover Operator,logical AND operator,various state preparation algorithms,and arithmetic comparators.
This Task focuses on the implementation of the MCX gate with a limited qubit count and circuit depth.

1.2 PROBLEM

Decompose an MCX gate with 14 control qubits into single-qubit and double-qubit CX gates. You may use up to five clean auxiliary qubits and should release(uncompute) them at the end of the circuit.Thus, the circuit can use no more than 20 total qubits: 14 control qubits,one target, and up to five auxiliary qubits.

IMPORTANT: Make sure that when you submit a circuit,the order of the qubits is indeed as follows: First the 14 control qubits, then the target qubit, then any auxiliary.This will help us validate the circuit.
