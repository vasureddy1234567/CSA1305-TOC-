# Experiment 37: Design and Simulation of a Nondeterministic Finite Automaton (NFA) Using Simulator

## Aim

To design and simulate a Nondeterministic Finite Automaton (NFA) to accept any number of b’s where input={a,b}.

---

## Problem Statement

Design an NFA for the language of strings consisting of any number of 'b's (including zero) over the alphabet {a,b}.

---

## Theory

An NFA for this language requires an initial state that is also an accepting state. This state loops on the character 'b'. Any input of 'a' will lead to a dead state implicitly (no transition defined).

---

## Input Alphabet

```
Σ = {a, b}
```

---

## Procedure

1. Open the simulation software.
2. Create the required states.
3. Mark the initial state.
4. Mark the accepting state(s).
5. Add the transitions according to the requirement.
6. Save the automaton.
7. Test the automaton using different input strings.
8. Verify whether the strings are accepted or rejected.

---

## Result

The NFA successfully accepts strings containing only 'b's.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2037%20-%20Output.png)
