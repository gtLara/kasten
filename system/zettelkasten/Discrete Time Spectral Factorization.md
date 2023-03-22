15-03-2023   23:02

Status: #idea
Tags: [[spectral]] 

A transfer function $H(z)$ has squared magnitude given by $|H(z)|^2$.The evaluation of $H(z)$ on the unit circle, $H(e^{j\omega})$, gives the frequency response of the filter. The frequency response in general is a complex function.

We can construct a filter $C(z)$ as follows

$$C(z) = H(z)H^*(1/z)$$

such that $C(e^{jw}) = |H(z)|^2$

*Discrete time spectral factorization* points in the other direction, decomposing a given $|H(z)|^2$ such that

$$|H(z)|^2 = H(z)H^*(1/z)$$

This leads to the possibility of designing multiple filters that have the same given squared magnitude function.

A geometric interpretation of spectral factorization is the positioning of repeated poles and zeros symmetric with respect to the unit circle such that the evaluation of the resulting transfer function on the unit circule corresponds to $|H(z)|^2$.

---


### Comes From

### Leads To

[[Deterministic "Shaping Filter"]]

### Related To

---

## References

[[Discrete Time Signal Processing - Oppenheim]] (299)