# election_project

Hi everyone! This is a project concerned with binary (categorical outcomes) in the 2016 election cycle, where I predict the voting outcome (D or R) for each county in the United States.

My methodology involves starting with a linear LASSO regression supported with 5-fold Cross-Validation. It was necessary to standardize my variables for this dataset, otherwise my predictions would likely be inaccurate by an order of magnitude for arbitrary measurement reasons. 

In addition to my LASSO regression, I also tune an elasticnet model to due to uncertainties in variables relevant to my model. I find the elasticnet model to have slightly better performance than LASSO regression. This serves as another way to validate our estimations.

For the first time, I also use a logistic regression to estimate outcomes. This is a step away from my prior linear modeling experience but represents a useful tool in estimating binary outcomes.

Finally, I also estimate an elasticnet logistic regression (!!) but find insignificant differences between the traditional logistic regression and the elasticnet model.

As always, the PDF has the cleanest formatting. :)

Metrics for model performance: accuracy, precision, specificity, and sensitivity.

