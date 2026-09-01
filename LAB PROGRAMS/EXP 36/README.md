# Experiment 36: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept the string that ends with "abc" over the set {a,b,c} and check if W = "abbaababc" is accepted.

---

## Problem Statement

Design a DFA for the language of strings over {a, b, c} that end with the substring "abc".

---

## Theory

A DFA ending in a specific pattern tracks the longest matching suffix of the pattern. For "abc", it needs states to represent seeing "", "a", "ab", and "abc" as the immediate trailing characters. Reaching the state representing "abc" means the string currently ends in "abc". Any deviation resets the state appropriately based on the new longest matching prefix of "abc" that is a suffix of what was just read.

---

## Input Alphabet

```
Σ = {a, b, c}
```

---

## Procedure

1. Open the simulation software.
2. Create the required states.
3. Mark the initial state.
4. Mark the accepting state(s).
5. Add the transitions according to the requirement.
6. Save the automaton.
7. Test the automaton using different input strings including "abbaababc".
8. Verify whether the strings are accepted or rejected.

---

## Result

The DFA successfully accepts strings ending with 'abc'. The string "abbaababc" is accepted.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2036%20-%20Output.png)
