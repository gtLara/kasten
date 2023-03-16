13-03-2023   11:47

Status: #idea
Tags: [[spectral]]

[[Parseval's Theorem]] leads to the following representation of a signal's power in the frequency domain, in which $F\{\}$ denotes the Fourier transform

$$ P = \lim_{T \to \infty} \frac{1}{2T}\frac{1}{2\pi} \int^{T}_{-T}|F\{x(t)\}(\omega)|^2 d\omega = \lim_{T \to \infty} \frac{1}{2T}\frac{1}{2\pi} \int^{T}_{-T}|X(\omega)|^2 d\omega$$

If $x(t)$ is square summable $P\to 0$   and it's spectral description is given by the [[Energy Spectral Density]].  If not, that is, if $x(t)$ is a power signal, the above definition makes sense since $P \to c$ , $c \neq 0$, but $X(\omega)$ is not well defined. Nevertheless in analogy to the [[Energy Spectral Density]] the _power spectral density_ can be defined as

$$ S_{x}(\omega) = \lim_{T \to \infty}\frac{1}{2\pi} \frac{1}{2T} |X(\omega)|² $$

This definition makes some sense since for $T < \infty$ $x(t)$ is a finite signal.

Here $S_x(\omega) d\omega$ represents the contribution of signal components of frequencies $\omega + d\omega$  to the signal power $P$. Note that in order for this definition to be convergent in $t \to \infty$ we must redefine $|X(\omega)|²$ by means other than a direct Fourier transform, leading to the [[Wiener-Khinchin theorem]].

---


### Comes From

[[Signal Power]]
[[Parseval's Theorem]]

### Leads To

[[Wiener-Khinchin theorem]]

### Related To

[[Energy Spectral Density]]

---

## References