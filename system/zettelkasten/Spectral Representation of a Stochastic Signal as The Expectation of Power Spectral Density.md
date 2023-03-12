12-03-2023   16:36

Supposing $Y(t)$ is an infinte realization of a stationary process we can define $X(t)$ as

$$
X(t) = 
\cases{
Y(t), -T < t < T \\
0, else
}
$$
Since $X(t)$ is now square summable we can define the Fourier of $X(t)$ transform, $F_x(\omega)$,  as 

$$ F_X(\omega) = \frac{1}{2 \pi} \int^{T}_{-T} X(t) e^{-j\omega t} dt = \frac{1}{2 \pi} \int^{T}_{-T} Y(t) e^{-j\omega t} dt $$

TODO: Understand this wayy better

---

Tags: [[spectral]]

### Comes From

[[impossibility of Fourier transform of a stationary signal]] 
[[signal energy]]
[[Signal Power]]
[[power density spectrum]]


### Leads To

### Related To

[[stationary signals as outputs of linear systems to random inputs]]


---

## References