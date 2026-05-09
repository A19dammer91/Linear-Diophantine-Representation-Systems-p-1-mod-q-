# Linear Diophantine Representation Systems — p ≡ 1 (mod q)

A complete theory of linear Diophantine systems N = pA + qB with p ≡ 1 (mod q). The minimal A-value always equals the digital root of N. Includes Additivity Theory, Matryoshka Theory, and proof that (19, 9) is the unique Class-IV pair.


## Core Results

**Main Theorem:** A₀ = dr(N) for every N ≥ pq

**Representation Formula:** R(N) = ⌊(⌊N/p⌋ − dr(N)) / q⌋ + 1

**Family Boundaries:** G(k) = 171k − 27

**Additivity Theory:** If a + b = c, representations sum simultaneously on three levels: numbers, coordinates, and digital roots.

**Matryoshka Theory:** Every value in the reduction chain N → S(N) → dr(N) appears as an A-coordinate in the representations of N.

The pair (19, 9) is proved to be the unique Class-IV pair.

## Python Code

See `core.py`, `system_19_9.py`, and `matryoshka.py`

## Publication

DOI: https://doi.org/10.5281/zenodo.20044995
