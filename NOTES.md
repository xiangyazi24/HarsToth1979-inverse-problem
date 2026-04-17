# Transcription Notes

## OCR Challenges

This paper was originally typeset on a typewriter (1979). The following ambiguities were encountered during transcription:

1. **p.366, $T \subset \mathbb{N}_0^?$**: The superscript in the original could be read as C or M. We use $\mathbb{N}_0^M$ since complexes are $M$-dimensional vectors of nonneg integers, consistent with the paper's later use of $y(n) \in \mathbb{N}_0^M$.

2. **p.375, canonic mechanism diagram**: In the middle tree (root $4Z$), the typewriter Greek letter $\gamma$ (gamma) closely resembles the Roman letter Y. This led to an initial misreading of the rate label $\gamma$ as a destination node "Y". The correct diagram has three branches from $4Z$:
   - $4Z \to X+4Z$ (rate $2\gamma$)
   - $4Z \to 4Z+V$ (rate $\gamma$)
   - $4Z \to 3Z$ (rate $4\gamma$)
   
   All three are confirmed by direct computation from the canonic construction applied to equation (3.4).

3. **p.379, address**: "Kulich Gyula tér" (correct Hungarian for the street near Semmelweis University).

## Mathematical Verification

All theorems, proofs, and examples have been verified independently:

- **Theorem 3.1** (necessary condition): The "lack of negative cross-effects" property follows directly from the mass-action form of the KDE.
- **Theorem 3.2** (sufficient condition): The canonic mechanism construction is verified to produce the correct KDE.
- **Example 3.1**: Both the canonic mechanism and the simple mechanism (3.5) produce the differential equation (3.4). Verified by computing all stoichiometric changes and mass-action rates.
- **Equation (2.1)**: The matrix form $Y[K - \operatorname{dg} K^T \mathbf{1}_N] x^Y$ equals the summation form $\sum_{p,q} k(p,q)(y(p)-y(q))x^{y(q)}$.

## Conclusion

No mathematical errors were found in the original paper. All issues were OCR/transcription artifacts.
