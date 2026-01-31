# FORMULAS.md — Mathematical Core of Coherent Time Theory (TCT)
## Canonical Relations (v1.0)

This document collects all **core mathematical relations** used in TCT.
No interpretation beyond operational meaning is assumed.

---

## 1. Coherence Field

The fundamental quantity of TCT is a scalar field:

𝓒 = 𝓒(x, t)

where:
- x denotes spatial coordinates,
- t denotes coordinate time,
- 𝓒 characterizes local temporal coherence.

𝓒 is not directly observable.

---

## 2. Action Functional

The dynamics of 𝓒 are defined by the action:

S[𝓒] = ∫ d⁴x √(-g) [ ½ g^{μν} (∂_μ 𝓒)(∂_ν 𝓒) − V(𝓒) ]

where:
- g_{μν} is the spacetime metric (treated as effective),
- V(𝓒) is a self-interaction potential,
- no specific form of V(𝓒) is fixed in v1.0.

---

## 3. Field Equation

Variation of the action yields the equation of motion:

□𝓒 − dV/d𝓒 = 0

where:
- □ = g^{μν} ∇_μ ∇_ν is the covariant d’Alembert operator.

This is the fundamental dynamical equation of TCT.

---

## 4. Stationary (Classical) Regime

In regimes where temporal gradients are suppressed:

∂ₜ𝓒 ≈ 0

the field admits quasi-static configurations.

---

## 5. Effective Gravitational Potential

Define an effective potential:

Φ ≡ κ · ln(𝓒)

where:
- κ is a proportionality constant (model-dependent, not fixed in v1.0).

---

## 6. Test-Body Acceleration

In the stationary regime, the acceleration of a test body is given by:

**a** = −∇Φ = −κ ∇ ln(𝓒)

This reproduces Newtonian gravity to leading order
for appropriate background configurations of 𝓒.

---

## 7. Temporal Fluctuations

Let y(t) be the fractional frequency deviation of a clock:

y(t) = δf(t) / f₀

Residuals after standard corrections are denoted:

δy(t)

---

## 8. Cross-Correlation Observable

For two clocks (1,2), define the cross-power spectral density:

S₁₂(f) = ⟨ δy₁(f) · δy₂*(f) ⟩

This quantity is directly measurable.

---

## 9. TCT Prediction

For frequencies below a cutoff f_c:

S₁₂(f) ≠ 0

with:
- positive correlation at zero lag,
- magnitude below individual clock noise,
- detectability via long-term cross-correlation.

---

## 10. Falsification Condition

If:

S₁₂(f) = 0  (within experimental sensitivity)

across the target frequency band,
then TCT v1.0 is falsified.

---

## 11. Phase Regimes (Reference)

Phases defined in PHASES.md correspond to regimes where different terms dominate:

- kinetic term: g^{μν} ∂_μ𝓒 ∂_ν𝓒
- potential term: V(𝓒)
- coupling via background metric

No additional equations are introduced for phases.

---

## 12. What Is Not Fixed

The following are intentionally unspecified in v1.0:
- explicit form of V(𝓒),
- quantum properties of 𝓒,
- coupling of 𝓒 back to g_{μν}.

These omissions are deliberate and required for falsifiability.

---

## Status

This document defines the **complete mathematical content** of TCT v1.0.
Any future formulas must be added as extensions, not modifications.
