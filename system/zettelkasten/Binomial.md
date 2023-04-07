07-04-2023   17:47

Status: #idea
Tags: [[probability]]


>[!definition]
The r.v. $X$ is said to have a *Binomial* distribution with parameters $n$ $\theta\in [0, 1]$ if its support set is $X(\omega) = \{0, 1, .., n\}$  with
$$P(X = k)= \frac{n!}{k!(n-k)!}\theta^k (1-\theta)^{n-k}$$

>[!corollary]
$$E(X) = n\theta$$ 

The binomial distribution arises from $n$ independent Bernoulli experiments by the counting of the total successes. $\theta$ still represents a chance of success and is constant across the $n$ experiments. The distributions' definition and expected value are intuitive and should be easily so.

---

### Comes From

[[Discrete Random Variable]]
[[Discrete Probability Distribution]]

### Leads To

[[Multinomial]]

### Related To

[[Geometric]]
[[Poisson]]
[[Binomial]]