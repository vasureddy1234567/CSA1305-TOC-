# Experiment 42: Design and Simulation of a Turing Machine (TM) Using Simulator

## Aim

To construct a Turing Machine to perform the function of Multiplication using Subroutines.

---

## Problem Statement

Design a Turing Machine that takes two unary numbers separated by a delimiter, multiplies them, and outputs the result in unary.

---

## Theory

Multiplication in a Turing Machine can be achieved using subroutines. Specifically, to multiply m and n, the machine repeatedly copies the second block of n '1's exactly m times. This involves an outer loop that iterates over the first number, and an inner subroutine that copies the second number to the output section of the tape.

---

## Input Alphabet

```
Σ = {1, *, =} (Example delimiters)
```

---

## Procedure

1. Open the simulation software.
2. Create the required states for the main logic and subroutines.
3. Mark the initial state.
4. Mark the accepting state(s).
5. Add the transitions (read, write, move direction).
6. Save the machine.
7. Test the machine using different unary inputs.
8. Verify whether the output matches the expected product.

---

## Result

The TM successfully performs unary multiplication.

---

## Conclusion

The Turing Machine was successfully designed and simulated. It correctly computes the product using subroutines, demonstrating the computational power and modular design of Turing machines using simulation software.

---

## Output

![Output](EXP%2042%20-%20Output.png)
