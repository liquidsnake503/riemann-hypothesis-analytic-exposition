# How a Zero off the Critical Line Would Force a Prime Sum to Grow

**Colin Feeney**  
24 November 2026

[Read the four-page manuscript (PDF)](RH_expo.pdf)

## Overview

This preliminary expository note presents a detailed analytic argument connecting zeros of the Riemann zeta function to positive excursions of a weighted prime-power sum. If a zero has real part greater than a fixed exponent θ > 0 in the critical strip, the note shows that the sum exceeds any fixed positive multiple of x^θ somewhere in every sufficiently late interval [Y, Y^(3/2)].

The argument uses the Mellin transform, high derivatives, concentration of a gamma distribution, and isolation of a nearest pole to control cancellation. The arithmetic window estimate is taken as an external input from the work of Levent Alpöge, as described in Propositions 2.4 and 2.5 of Slijepčević's exposition. The analytic result expands on the zero-exclusion principle outlined in Proposition 2.2 of that exposition.

For $1/2\le\theta<\Re\rho$, Lee Crossley gives a measure bound for the excursions in Theorem 2. For every $M>0$ and $\varepsilon>0$, the set where $G(x)>Mx^\theta$ has Lebesgue measure greater than $Y^{3/2-\varepsilon}$ in every sufficiently late window $[Y,Y^{3/2}]$. [The Crossley Criteria, §11.3](https://doi.org/10.5281/zenodo.24466908) and [Lean theorem](https://github.com/leecrossley/crossley-criteria-riemann-hypothesis/blob/fa2da5e5cd92579184537f49d569230db76f6026/project/src/ArchiveFreeBadMeasure.lean#L664-L669).

## Scope and verification status

This is an AI-assisted mathematical exposition, not a claim to an independent proof of the Riemann hypothesis or to priority for Alpöge's result. The deep arithmetic estimate is not proved here. The manuscript has not been peer reviewed or independently verified in full, and corrections and mathematical feedback are welcome. Verification of the external Lean development should not be confused with verification of this note.

## AI assistance

OpenAI ChatGPT was used extensively in developing the mathematical argument, drafting the manuscript, and preliminary review. Its contribution was substantive, not limited to editing or formatting. The note is shared as a preliminary draft; readers should independently check the arguments and external dependencies.

## References

1. L. Alpöge, [Announcement and formal proof archive references](https://alpo.ge/remark.pdf), 20 November 2026.
2. S. Slijepčević, [Outline of Alpöge's proof of the generalised Riemann hypothesis](https://hexagonmath.org/pdf/2611.00812), 21 November 2026, Section 2, especially Propositions 2.2, 2.4 and 2.5.
3. Lean FRO and Mathlib Initiative, [Lean verification of the Riemann Hypothesis](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/), 21 November 2026.
