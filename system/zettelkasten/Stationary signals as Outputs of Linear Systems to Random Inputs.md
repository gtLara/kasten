16-03-2023   14:47

Status: #idea
Tags: [[random_signals]]

Stationary signals can be seen as a result of the processing of random signals by a linear system. Assuming that a random signal $x[n]$ is processed by a filter of transfer function $h[n]$ resulting in the output signal $y[n]$ we can write

$$ y[n] = x[n]*x[n] $$

A spectral representation is limited to the description of the squared magnitude of the random signals ([[Spectral Representation of a Stochastic Process]]), therefore

$$S_y(\omega) = S_x(\omega) |H(j\omega)|^2$$

We note that for any given input output relationship there are multiple filters that statisfy the spectral transfer. The choice of the minimum-phase stable filter lead to the idea of a [[Shaping Filter]].

---

### Comes From

[[Spectral Representation of a Stochastic Process]]

### Leads To

[[Shaping Filter]]

### Related To

[[ARMA processes as the linear processing of white noise]]

---

## References

[[Introduction to Random Signals and Applied Kalman Filtering - Brown & Hwang]](130)