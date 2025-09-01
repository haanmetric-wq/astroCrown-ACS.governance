# Ethical Clauses — AstroCrown ACS (v0.1)

## Purpose
Protect token holders and ecosystem participants by enforcing transparent, reproducible, and dignity‑preserving rules.

## Invariants
- LCR = 1.00 at all times using the pure (fee‑free) floor: F_pure = reserves / circulating_supply.
- Safe releases only if projected post‑trade LCR ≥ 1.00 and feasibility holds (fee‑aware).
- No hidden buffers in floor computation; fees never inflate the floor.

## Transparency & Reproducibility
- Publish configs, seeds, and data manifests; tag immutable releases.
- Record every decision with inputs, checks, and outcomes.

## Venue & Execution Fairness
- External venues: fee‑aware triggers may print below floor due to platform fees, gas, and slippage.
- AstroCrown Platform: only gas fees; triggers closer to the official floor.

## Oracle Integrity
- Committee‑based consensus (min 2‑of‑3) with tolerance and staleness gates (empirically derived).
- Pause on divergence beyond gates; resume on consensus.

## Change Control
- Any policy change requires simulation evidence, ethics review, and a new tagged config.
- Emergency pauses are allowed under documented criteria, with post‑mortem publication.

## Public Communication
- State fee policy clearly; distinguish official floor (fee‑free) from execution triggers (fee‑aware).
