22-03-2023   15:50

Status: #idea
Tags: [[algebra]]

>[!definition]
The set of all combinations of a list $X$ of vectors $(v_1, ..., v_n)$  in V is called the *span* of $X$, denoted $span(X) = span(v_1, ..., v_n)$.

$$span(v_1, ..., v_n) = \{\lambda_1v_1 + \lambda_2v_2 + ... + \lambda_nv_n: \lambda_1, \lambda_2, ..., \lambda_n \in \mathbf{F}\}$$

>[!corollary]
By the above writing of span it is clear that the *span of a list of vectors of a vector space is a subspace*, since it contains the zero vector (setting $\lambda_i = 0 \forall i$), is closed under addition (since the field coefficients can be grouped) and under scalar multiplication, since the scalar value is distributed along the linear combination. Thus we can write $[X]$ as the vector space equal to the span of $X$.


If $span(X)$ is equal to a subspace $W$ it is said that $X$ spans $W$.

---


### Comes From

[[Vector Space]]
[[Linear Combination]]

### Leads To

[[Finite Dimensional Vector Space]]
[[Basis]]
[[Dimension]]

### Related To