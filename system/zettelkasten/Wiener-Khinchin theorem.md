
14-03-2023   14:23

Status: #idea
Tags: [[autocorrelation]]

Picking up from the definition of power spectral density
$$ S_{x}(\omega) = \lim_{T \to \infty}\frac{1}{2\pi} \frac{1}{2T} |X(\omega)|² $$

We observe that 

$$ |X(\omega)^2| = X(\omega)X^*(\omega) = F(F^{-1}(X(\omega))*(F^{-1}(X^*(\omega))) = F(x(t) * x^*(-t)) = F(x(t) * x(-t))$$

This final operation, convolution of a signal with a mirror image of itself, is exactly the correlation of a signal with itself (autocorrelation). Thus, not assuming ergodicity, we can write

$$E[|X(\omega)_T|^2] = \frac{1}{2\pi}\int_{-T}^{T} \rho(t)e^{-j \omega t}dt$$

This leads to the Wiener-Khinchin theorem for ergodic and stationary processes

$$|X(\omega)_T|^2 = \frac{1}{2\pi}\int_{-T}^{T} \rho(t)e^{-j \omega t}dt$$

Assuming that the expectation is convergent at the limit $T \to \infty$  we have

$$ |X(\omega)|^2 = \frac{1}{2\pi} \int^{\infty}_{-\infty} \rho(t) e^{-j\omega t}dt$$ 

---

### Comes From

[[Power Spectral Density]]

### Leads To

[[Spectral Representation of a Stochastic Process]]

### Related To

---

## References


