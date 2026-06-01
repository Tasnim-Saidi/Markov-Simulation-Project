# Markov Chain — Word Generator

A university project for the **Stochastic Processes** course (ING1 Informatique, ENICarthage 2025/2026).

Implements a **first-order Markov chain** to generate new words that sound like they belong to a real language, based on a dictionary input.

---

## How It Works

1. **Initial distribution π(0)** — extracts the probability of each letter appearing as the first letter of a word.
2. **Transition matrix P** — computes the probability of each letter following another, based on all consecutive letter pairs in the dictionary.
3. **Word generation** — starts with a random first letter (following π(0)), then picks each next letter using the transition matrix, until an end-of-word character `#` is reached.

---

## Files

| File | Description |
|---|---|
| `Markov_Simulation_Project.ipynb` | Python notebook — core logic, matrix computation, word generation |
| `Markov_Simulation.html` | Interactive browser demo — paste a dictionary, adjust parameters, generate words |

---


## Tech Stack

Python · NumPy · HTML · CSS · JavaScript

---

## Course

Processus Stochastiques — I. Kammoun · ENICarthage · 2025/2026
