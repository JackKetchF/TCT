# EXPERIMENT.md — Experimental Tests of Coherent Time Theory (TCT)
## Minimal, Falsifiable Program (v1.0)

This document defines a **single primary experimental test** of TCT and two secondary consistency checks.
The goal is falsification, not confirmation.

---

## Primary Test: Correlated Noise in Precision Clocks

### Motivation

In TCT, fluctuations of the coherence field 𝓒(x,t) induce **correlated residual timing noise**
between spatially separated clocks, after all standard corrections are applied.

General Relativity predicts **no such correlations** beyond known gravitational, environmental,
and instrumental effects.

---

### Observable

Let:
- δy₁(t), δy₂(t) be fractional frequency residuals of two clocks,
- after removing:
  - gravitational redshift,
  - relativistic time transfer effects,
  - tidal effects,
  - known environmental couplings.

Define the cross-power spectral density (CPSD):

S₁₂(f) = ⟨δy₁(f) · δy₂\*(f)⟩

---

### TCT Prediction

For sufficiently low frequencies f < f_c:

S₁₂(f) ≠ 0

with:
- positive correlation at zero lag,
- coherence decreasing with spatial separation,
- a low-frequency-dominated spectrum.

---

### Expected Magnitude (Order of Magnitude)

Based on existing clock noise floors:

- Optical lattice clocks:
  Allan deviation σ_y ≈ 10⁻¹⁸ at τ ≈ 10³–10⁴ s

TCT-compatible correlated component (target sensitivity):

σ_corr ≈ 10⁻²¹ – 10⁻²⁰

This lies:
- **below single-clock noise**,
- **above cross-correlation detection thresholds** in long integrations.

---

### Frequency Window

Primary sensitivity band:

f ≈ 10⁻⁵ – 10⁻³ Hz

Rationale:
- Below dominant seismic and thermal noise,
- Above long-term drift systematics.

---

### Experimental Setup (Minimal)

1. Two or more independent optical clocks.
2. Separation:
   - laboratory-scale (10–100 m), or
   - inter-laboratory (100–1000 km).
3. Independent lasers, electronics, and environmental isolation.
4. Time transfer via stabilized optical fiber or satellite link.
5. Long integration time (weeks to months).

---

### Data Analysis Protocol

1. Apply standard relativistic corrections.
2. Remove known correlated environmental signals.
3. Compute CPSD S₁₂(f).
4. Estimate statistical significance via time-shifted null tests.
5. Compare against simulated noise-only models.

---

### Falsification Criterion

If, within stated sensitivity:
- S₁₂(f) is consistent with zero across the target band,
- and upper bounds fall below σ_corr,

then **MODEL.md v1.0 is falsified**.

No parameter tuning rescues the model.

---

## Secondary Test A: Spatial Scaling

Prediction:
Correlation strength decreases monotonically with separation distance.

Test:
Repeat primary experiment at multiple baselines.

---

## Secondary Test B: Clock-Type Independence

Prediction:
Correlation depends weakly on clock species
(optical lattice vs. ion clocks).

Test:
Cross-correlate heterogeneous clock types.

---

## Relation to Existing Data

Public datasets from:
- NIST,
- PTB,
- SYRTE,

report unexplained low-frequency noise components.
These datasets **may already constrain or falsify TCT**, pending cross-correlation analysis.

---

## Scope and Limits

- TCT does not predict signals at high frequencies.
- No violation of causality or signal propagation occurs.
- Absence of correlation conclusively rejects the theory.

---

## Status

This document defines the **minimal experimental gateway** for TCT.
No additional experiments are required to test the core model.
