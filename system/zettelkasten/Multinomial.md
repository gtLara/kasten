07-04-2023   18:27

Status: #idea
Tags: [[probability]]

---

>[!definition]
A vector r.v. $\mathbf{N}=(N_1, N_2, ..., N_k)$ has a multinomial distribution with parameters $n$ and $\theta_1, ..., \theta_k$ with $\theta_i > 0$ and $\sum \theta_i=0$ if the support set is
$$X(\omega) = (x_1, x_2, ..., x_k) : x_i \in \{0, 1, ..., n\}, \sum x_i =n $$
and associated probabilities given by 
$$P(\mathbf{N})= \frac{n!}{n_1 ! n_2 ! ... n_k !} \theta^{n_1}_1 ... \theta^{n_k}_k$$

>[!corollary]
$$E(X_i) = n\theta_i$$ 

The multinomial distribution generalizes the binomial distribution to $n$ experiments with $k$ possible outcomes or categories. Note that the binomial distribution is a multinomial distribution with $k=2$. 

We denote a vector of results from a multinomial distribution as 

$$\mathbf{N}=(N_1, N_2, ..., N_k) \textasciitilde \mathcal{M}(n, \theta_1, \theta_2, ..., \theta_k)$$

---

### Comes From

[[Binomial]]
[[Discrete Random Variable]]
[[Discrete Probability Distribution]]

### Leads To

### Related To

[[Geometric]]
[[Poisson]]
[[Multinomial]]


### Comes From

### Leads To

### Related To

---

## References