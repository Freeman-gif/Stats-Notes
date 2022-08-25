# Residulas


---
### Notes and Ideas:

**Defination**:

- Residuals in a statistical or machine learning model are the differences between observed and predicted values of data. They are a diagnostic measure used when assessing the quality of a model. They are also known as errors 

**Use** :
- Residuals are importatant when determining the quality of a model. We can examine residuals in terms of their mahnitude and/ or whether they form a parttern
- Where the residuals are all 0, the model predicts perfectly. THe further residuals are from 0, the less accurate the model. In the case of [[Linear Regression]], the greater the sum of squared residucals, the smaller the r-squared tatistic, all else being equal
- Where the average residual is not 0, it implies that the model is systematically biased(i.e., consistently over-or under-predicting)

**Residual plot**:
-   In the case of simple linear regression (regression with 1 predictor), we set the **predictor** as the x-axis and the residual as the y-axis
-   In the case of multiple linear regression (regression with >1 predictor), we set the **fitted value** as the x-axis and the residual as the y-axis


**Residcual function**:
$$res = y-\hat{y}$$
$$ =y - (\hat{b_0}+\hat{b_1}x_1+\hat{b_2}x_2+......+\hat{b_n}x_n)$$



---

### Key words:

---
#### TAGS