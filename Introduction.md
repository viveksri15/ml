# Elements of Statistical Learning

## Introduction

**Supervised Learning**: It is supervised learning because presence of outcome variables in training data guide the learning process.

**Unsupervised Learning**: It is unsupervised learning because there is no such known outcome variables in training data, and outcomes have to be derived.

**Classification problem** like email spam detection is a supervised learning process with outcome variables creating classifications.

**Regression problems** like predicting price of a house given some input variables is also supervised learning, with outcome variables being quantitative.

**Clustering** is an unsupervised learning process.


## Supervised Learning

In statistical literature, the input variables are called **predictors**, otherwise also known as **independent variables**, or **features**. The output variables are also called **response** or **dependent variables**.

Variables can be quantitative (comparable numbers) or qualitative (like class of variables eg. spam/not-spam). Qualitative variables are also called **categorical** or **descrete** variables or **factors**.

**Ordered categorical** variables are those where ordering exists, but are qualitative. For example, *small*, *medium*, *large*.

Numeric codes representing qualitative variables are also called **targets**.

### Linear models and Least Squares

For an input vector X^T = (X^1 X^2 ... X^p), we can write 

					Ŷ = \beta_0 + \sum_{j=1}^{p} X_j\beta_j