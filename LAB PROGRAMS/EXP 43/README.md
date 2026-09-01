# Experiment 43: Design and Simulation of a Finite Automaton (FA) Using Simulator

## Aim

To construct a Finite Automaton (FA) Machine to check string of binary characters, check if it is a multiple of 3.

---

## Problem Statement

Design a DFA for the language of binary strings that represent a number divisible by 3.

---

## Theory

A DFA can evaluate binary numbers divisible by 3 by tracking the remainder modulo 3. The states represent remainders 0, 1, and 2. Reading a '0' shifts the value (multiplies by 2), so remainder 1 becomes 2, remainder 2 becomes 1 (since 4 mod 3 = 1). Reading a '1' shifts and adds 1, so remainder 0 becomes 1, remainder 1 becomes 0 (3 mod 3 = 0), and remainder 2 becomes 2 (5 mod 3 = 2). The state representing remainder 0 is the accepting state.

---

## Input Alphabet

```
Σ = {0, 1}
```

---

## Procedure

1. Open the simulation software.
2. Create the required states (q0, q1, q2).
3. Mark the initial state (q0).
4. Mark the accepting state(s) (q0).
5. Add the transitions according to the modulo logic.
6. Save the automaton.
7. Test the automaton using different binary input strings.
8. Verify whether the strings are accepted or rejected based on their decimal equivalent.

---

## Result

The FA successfully accepts binary strings that are multiples of 3.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly processes strings based on the mathematical condition, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2043%20-%20Output.png)
