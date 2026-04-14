# HADC: Hybrid Adaptive DNA Compression

An interactive visualization of a multi-stage DNA compression pipeline combining streaming algorithms, dynamic programming, and entropy coding.

---

## Project Overview

HADC (Hybrid Adaptive DNA Compression) is a simulation tool that demonstrates how DNA sequences can be efficiently compressed using a combination of:

* Misra-Gries Algorithm (heavy hitter detection)
* Binary Splitting
* Bounded Knapsack (Dynamic Programming)
* Hybrid LZ-style Encoding
* Arithmetic Coding (Entropy Optimization)

This project is designed for educational and demonstration purposes, showing how different algorithmic paradigms work together in a real-world pipeline.

---

## Features

* Step-by-step animated pipeline
* Random DNA sequence generation
* Dynamic programming table visualization
* Heavy-hitter filtering using Misra-Gries
* Optimal dictionary selection via Knapsack
* Token-based hybrid encoding
* Compression comparison (Greedy vs Knapsack)
* Entropy-based optimization using Arithmetic Coding

---

## Algorithms Used

### 1. Misra-Gries Algorithm

Efficiently finds frequent k-mers using limited memory.

### 2. Binary Splitting

Transforms bounded frequency items into 0/1 items for dynamic programming.

### 3. Bounded Knapsack (Dynamic Programming)

Selects optimal k-mers under capacity constraints.

### 4. Greedy Approach

Used for comparison to highlight suboptimal decisions.

### 5. Hybrid Encoding

Combines:

* Dictionary references (similar to LZ techniques)
* Literal encoding

### 6. Arithmetic Coding

Applies entropy compression to approach the theoretical minimum number of bits.

---

## How to Run

### Option 1: Live Demo

Open in browser:

```
https://hari235676-del.github.io/HADC/index.html

--
## Project Structure

```
HADC/
│── index.html     # Main visualization and logic
│── README.md      # Documentation
```

---

## Output Metrics

* Compression Ratio
* Bits Saved
* Entropy Estimate
* Greedy vs Knapsack Performance

---

## Key Insight

Greedy selection prioritizes locally optimal patterns with high density, often leading to a larger dictionary. In contrast, the bounded knapsack approach identifies globally optimal selections that minimize overall encoding cost by reducing dictionary size and index overhead.

---

## Applications

* Bioinformatics data compression
* Efficient genome storage
* Algorithm visualization for teaching
* Comparative analysis of optimization techniques

---

## Authors

Jennica Hanlynn Suhan

Tresa Mathew

Hari Nandana

---

## License

This project is for academic and educational use.
