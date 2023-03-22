16-03-2023   13:55

Status: #idea
Tags: [[spectral]] [[random_signals]]

The actual shaping filter is defined in a much similar way to the deterministic shaping filter -
the diference being that we now assume the linear system is excited by a random signal. Since a spectral description of random signals is restricted to the expectation of their spectral squared magnitude we are limited to the transfer of this property between intput, filter, and output. The idea of a shaping filter then arises as the filter responsible for processing a white signal to produce a stationary random signal as output - "shaping" the 
flat input spectrum into the output spectrum. Taking $H(z)$ as a filters transfer function and $S_y(\omega)$ as the spectrum of the output signal we have the following relation if $H(z)$ is excited by a white signal

$$S_y(\omega) = \frac{\sigma_\varepsilon}{2\pi} |H(\omega)|^2 $$

Taking $\omega = z$ and performing spectral factorization on both sides of the equation above we have

$$S_y^{-}(z)S_y^{+}(z) = \frac{\sigma_\varepsilon}{2\pi}H(z)H^*(1/z)$$

Where $S_y^{-}(z)$ represents the spectral factor of $S_y(\omega)$ that contains all poles and zeros within the unit circle. Note that spectral factorization on $S_y(\omega)$ is consistent with our definition because it represents a real valued square magnitude.

We can now discard the poles and zero outside the unit circle and take the inverse path of modelling $H(z)$ as 


$$ H(z) = \frac{2\pi}{\sigma_\varepsilon} S_y^{-}(z) $$

Recall from [[Discrete Time Spectral Factorization]] that $H(z)\frac{\sigma_\varepsilon}{2\pi}$ should have squared magnitude equal to $S_y(z)$ 


---


### Comes From

[[Deterministic "Shaping Filter"]]
[[Discrete Time Spectral Factorization]]
[[Spectral Representation of a Stochastic Process]]
[[Stationary signals as Outputs of Linear Systems to Random Inputs]]

### Leads To


### Related To


---

## References

[[Introduction to Random Signals and Applied Kalman Filtering - Brown & Hwang]](137)