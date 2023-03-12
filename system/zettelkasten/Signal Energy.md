12-03-2023   17:57

Status: #idea
Tags:

---

The energy $E$ of a signal $x(t)$ is defined as 

$$ E = \int^{\infty}_{-\infty} |x(t)|^2 dt $$

In which the modulo operation is used probably to account for complex analytic signals (like fasors). This definition is only loosely coupled with physical energy since a signal by itself cannot convey the physical context necessary to adequately determine the system's energy.

To use an electrical example we can think of a voltage signal $v(t)$ loaded by a real impedance $R$ such that the system's energy is given by

$$ E_{physical} = \frac{1}{R}\int_0^{T} v(t)^2 dt$$

In terms of the voltage signal energy $E_v$ we can write

$$ E_{physical} = \frac{1}{R} E_v$$

From which we understand that the voltage signal energy does not convey the system's physical energy because it lacks the "missing context" of the load resistence. 

It has become clear that the signal energy is a signal property and the physical energy a system property. From this interpretation the relationship between signal and system energy extends only to proportionality, such that

$$E_{physical} \hspace{5mm} \alpha \hspace{5mm} E_{signal}$$


### Comes From

### Leads To

[[Energy Spectral Density]]

### Related To

[[Signal Power]]

---

## References

https://math.stackexchange.com/questions/7924/how-can-i-interpret-energy-in-signals

https://www.quora.com/What-is-the-physical-significance-of-the-energy-of-a-signal-Is-it-equal-to-the-square-of-the-magnitude

https://en.wikipedia.org/wiki/Energy_(signal_processing)