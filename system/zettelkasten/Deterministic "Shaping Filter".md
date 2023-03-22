15-03-2023   23:19

Status: #idea
Tags: [[spectral]]

From spectral factorization it is known that

$$|H(z)|^2 = H(z)H^*(1/z)$$

If we restrict $H(z)$ to be stable, causal and minimum-phase (invertible) $H(z)$ is unique for a given $|H(z)|²$. This unique $H(z)$ is called a *shaping filter*, deterministic by this definition, so called because it shapes the observed $|H(z)|²$.

This is, to a certain extend, a strech of nomenclature -  the term is used tipically for the processing of random signals.

Following the geometric interpretation posed in [[Discrete Time Spectral Factorization]] we can imagine the following procedure: given a desired $|H(z)|^2$ we can perfeorm spectral factorization. Assuming that the resulting $H(z)$ is causal, stable and invertible all of its poles and zeros lie inside the unit circle and all of $H^*(1/z)$ 's poles and zeros are symmetric with respect to the unit circle. We then choose the poles and zeros inside the unit circle to define our shaping filter, which is $H(z)$.

---

### Comes From

[[Discrete Time Spectral Factorization]]

### Leads To

[[Shaping Filter]]

### Related To

---

## References

[[Discrete Time Signal Processing - Oppenheim]]
[[Introduction to Random Signals and Applied Kalman Filtering - Brown & Hwang]]