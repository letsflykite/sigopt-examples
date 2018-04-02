[![image](https://sigopt.com/static/img/SigOpt_logo_horiz.png?raw=true)](https://sigopt.com)

# SigOpt Constraints R Example

Here we demonstrate defining constraints for SigOpt experiments in R.

We will be optimizing a constrained version of the [Adjiman Function](http://benchmarkfcns.xyz/benchmarkfcns/adjimanfcn.html).

## R
Simply add your SigOpt [API token](https://sigopt.com/docs/overview/authentication) in line 11 of `constraints.R` and then execute the R script in R Studio, or in the terminal:

```
RScript constraints.R
```

You can follow the experiment on your [experiment dashboard](https://sigopt.com/experiments).

Learn more about our [R API Client](https://sigopt.com/docs/overview/r).

## Questions?
Any questions? Drop us a line at [support@sigopt.com](mailto:support@sigopt.com).

## API Reference
To implement SigOpt for your use case, feel free to use or extend the code in this repository. Our [core API](https://sigopt.com/docs) can bolt on top of any complex model or process and guide it to its optimal configuration in as few iterations as possible.

## About SigOpt

With SigOpt, data scientists and machine learning engineers can build better models with less trial and error.

Machine learning models depend on hyperparameters that trade off bias/variance and other key outcomes. SigOpt provides Bayesian hyperparameter optimization using an ensemble of the latest research.

SigOpt can tune any machine learning model, including popular techniques like gradient boosting, deep neural networks, and support vector machines. SigOpt’s REST API and client libraries (Python, R, Java) integrate into any existing ML workflow.

SigOpt augments your existing model training pipeline, suggesting parameter configurations to maximize any online or offline objective, such as AUC ROC, model accuracy, or revenue. You only send SigOpt your metadata, not the underlying training data or model.

SigOpt is available through [Starter, Workgroup, and Enterprise plans](https://sigopt.com/pricing), and is [free forever for academic users](https://sigopt.com/edu).
