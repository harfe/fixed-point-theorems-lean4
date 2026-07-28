# Kakutani fixed-point theorem and Brouwer fixed-point theorem formally proven in Lean 4


The proofs are complete. no sorrys. Relies on Mathlib.


## About the approach

The proof for the Kakutani fixed-point theorem relies on the Brouwer fixed-point theorem
(and partition of unity and Caratheodory's theorem).

The proof for the Brouwer fixed-point theorem relies on a cubical version of Sperner's Lemma.
See Kuhn, 1960, "Some Combinatorial Lemmas in Topology" for this approach.

## Build

Requires Lean 4 (`v4.30.0`) and Mathlib (`v4.30.0`).

```bash
lake exe cache get
lake build FixedPointTheorems
lake env lean scripts/AxiomAudit.lean
```
