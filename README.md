# math-157---formalizing-handshake-

# Formalizing the Handshaking Lemma in Lean 4

This repository contains the final project for the math157 course. It implements a fully machine-checked proof of the **Handshaking Lemma** (Graph Theory) using the **Lean 4** theorem prover and `Mathlib`.

## Project Components
1. **The Code (`Handshaking.lean`):** A formalization of the theorem stating that the sum of vertex degrees in a finite graph equals twice the number of edges. It demonstrates finite set summations (`Finset.sum`), axiomatic scope bounding for quotient types (`Sym2`), and corollary derivations regarding degree parity.
2. **The Documentation (`Comparative_Review.pdf`):** A comparative review analyzing the architectural and automated-proving trade-offs between Lean 4 (Dependent Type Theory) and Isabelle/HOL.

