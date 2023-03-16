
12-03-2023   18:31

Status: #idea
Tags: 

 In the equation for a signal's energy $|x(t)|^2dx$  can be recognized as a density function multiplied by an infinitesimaly small time interval that describes the energy contained in $x(t)$ at the time interval $t + dt$. By [[Parseval's Theorem]]

$$ E = \int^{\infty}_{-\infty} |x(t)|^2 dt = \frac{1}{2\pi} \int^{\infty}_{-\infty} |F\{x(t)\}(\omega)|^2 d\omega$$
where $F\{\}$ denotes a Fourier transform.  Rewriting the above as

$$ E = \frac{1}{2\pi}\int^{\infty}_{-\infty} |X(\omega)|^2 d\omega $$
We equally have $|X(\omega)|^2$ representing an energy density function, called the _energy spectral density_ function.

---


### Comes From

[[Parseval's Theorem]]
[[Signal Energy]]

### Leads To

### Related To

[[Power Spectral Density]]

---

## References

