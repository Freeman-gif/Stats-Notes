# Ridge Regression($l1$ Penalty)


---
### Defination and Ideas:
- In ridge Regression, the cost function is altered by adding a penalty equivalent to square of the magnitude of the coefficients:
	- $$\sum_{i=1}^{M}(y_i-\hat{y_i})^2=\sum_{i=1}^{M}(y_i-\sum_{j=0}^{p}w_j\times x_{ij})^2 + \lambda \sum_{j=0}^{p}w_j^2$$ 
	- equivalent to saying minimizing the cost function in equation under the condition that for some c>0, $\sum_{j=0}^{p}w_j^2 < c$
- The ridge regression puts **constraint** on the coefficients($w$). Then penalty term($\lambda$) **regularizes** the coefficients such that ==if the coefficients take large values the optimization function is penalized==.  



---
