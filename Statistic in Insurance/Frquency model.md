# Frquency model

                          
Previously, we discussed several discrete distributions and their properties. In this set of notes, we will further develop properties of these distributions and discuss  
when they might be appropriate for claims counts.  
Recall the[[Binomial distribution]], [[Poisson Distribution ]], and [[Negative Binomial Distribution]].  The [[Binomial distribution]] had a mean of $np$ and a variance of  $np(1-p)$. The ____________________ distribution had a mean of _________  and a variance of _____________. The _________________________ distribution  had a mean of ____________ and variance of ___________.  Consequently, one determining factor on which distribution might be appropriate  is to compare the mean and variance.  
Alternatively, if we assume that all risks are identical an independent and that  they have the same (constant) chance of a claim, then the __________________  would be appropriate.  If n is large and p is small, then the binomial distribution can be reasonably  approximated with a [[Poisson Distribution]] where $\lambda = np$.
==note: for really large n, we can model Probability ==

While the [[Poisson Distribution]] can reasonably approximate a [[Binomial distribution]] for large n and small p, because we areusing one parameter, the approximation  can be somewhat restrictive .  Since the [[Negative Binomial Distribution]] has two parameters, it can provide us with  some additional flexibility. In fact, we can generalize the [[Negative Binomial Distribution]] to make sense for non-integer values of r.  
==using the gamma funciton $P(x=k) = $==
All of these distributions (and the geometric) have something in common.  together, they make up what is known as the (α, β, 0) family. All of these  distributions can be described by a recursive relationship of the form 


$$p(x) = (\alpha+\frac {\beta}{x})p(x-1)$$

| Distribution      | $\alpha$   | $\beta$   | $p(0)$         |
| ----------------- | ---------- | --------- | -------------- |
| Posiion           | 0          | $\lambda$ | $e^{-\lambda}$ |
| Megative Binomial | 1-p | (1-P)  |     $p^r$            |














**Further discussion of the Poisson**  

Previously, we discussed that the sum of independent Poisson random variables  was Poisson random variable  

iid => independent and identical distributed 






Consider X1, X2, ...,Xk to be independent Poisson random variables with parameters λ1, λ2,, ..., λk, then S = X1 + X + ... + Xk satisfies.  Now supposed that X is the total number of claims and X has a Poisson(λ)  
distribution and suppose that X is made up of events that can be classified as one  and only one of k distinct types. Let pi denote the probability that the event is of  type i and Xi denote the number of claims of type i. Then X1, X2, ...,Xk are  independent and each has a [[Poisson Distribution]] with parameter $\lambda_i$. This is called the Decomposion property of the [[Poisson Distribution]].

$p(x = m)= p(x_1=m)p_1+p(x_2=m)p2+ .....p(x_k)p_k$
=$$



Example :
| Driver | Proportion of the Driver | Frequency Distribution Poisson
| ------ | ------------------------ |




---
Modification of zero
what is the frequency distributioin has a probability at zero that doesn't fit into the pattern?
Then we can get ($\alpha,\beta,1$) distribution separately and handle all other cases with our formula




Case 1: zero Truncated:
- p(0) = 0 (zero is not an option), let p(x) denote the original Probability using a tradional model adn we let $P_{zt}(x)$ denote to the zero truncated model, $p_{zt}(x) = \frac {p(x)}{1-P(0)}$


Case 2: zero modified
	-let $p_{zt}$ denote zero modified, zero is an outcome but it doesn't fit our pattern
	$P_z$


---
## Notes and Ideas:
---
### Key words:
---
#### tags:









	

