# Home-Credit-Default-Risk
The goal of this project is to classify and predict the number of clients that can receive a 
loan. I classified people as clients who are to be granted a loan, and the ones who the
business would not lend to. This highlights the reliability or credibility of an applicant for
repayment of the loan and whether they can pay.

The problem in particular strikes as challenging to solve since this business works in an unusual
scenario where loans are to be granted to people that other banks would normally not consider,
given the low to zero credit score. Since their business model is focused upon granting loans to
individuals that other banks would demonstrably refuse, they are at a significantly higher
financial risk. As a result, the business would save by mitigating at-risk clients while yielding
profits by making use of the methods on the dataset to solve the issue at the highest possible
accuracy, comparatively more than they would gain without using the models.
Next, the data was cleaned and pre-processed in ways that made it suitable for use in various
modeling approaches.

I tuned two types of classification models using either all predictors or a subset of the data that had near-zero
variance and highly correlated predictors removed. This phase included using the predictive
clustering models like **K-means and logistic regression analysis**, and
classification models such as **decision trees, Naïve Bayes Gaussian NB and Logistic Regression** to classify the population in no risk categories and
at risk categories considering data of each individual such as low credit score, family income as
variables of the model, credit card balance, previous applications. I also used **H2O Generalized Linear Estimator** for achieving the best accuracy for the last model

