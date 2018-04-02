[![image](https://sigopt.com/static/img/SigOpt_logo_horiz.png?raw=true)](https://sigopt.com)

# sigopt-beats-vegas

Learn more at the associated [blog post](http://blog.sigopt.com/post/136340340198/sigopt-for-ml-using-model-tuning-to-beat-vegas).

Dive right in with [the iPython Notebook](https://github.com/sigopt/sigopt-examples/blob/master/sigopt-beats-vegas/SigOpt%20NBA%20OverUnder%20Model.ipynb).

## Setup

1. Get a free SigOpt account at https://sigopt.com/signup
2. Find your `client_token` on the [API tokens page](https://sigopt.com/tokens) and set it
  as the `SIGOPT_API_TOKEN` environment variable.
4. Run `sudo ./setup_env.sh`

## Run

We recommend using [Jupyter](http://jupyter.readthedocs.org/en/latest/install.html) to walk through this example. Start Jupyter (run `jupyter notebook`), then open:

[`SigOpt NBA OverUnder Model.ipynb`](https://github.com/sigopt/sigopt-examples/blob/master/sigopt-beats-vegas/SigOpt%20NBA%20OverUnder%20Model.ipynb)

To run the predictor as a standalone:
```
cd predictor
python stand_alone.py
```

## Questions?
Any questions? Drop us a line at [support@sigopt.com](mailto:support@sigopt.com).

## API Reference
To implement SigOpt for your use case, feel free to use or extend the code in this repository. Our [core API](https://sigopt.com/docs) can bolt on top of any complex model or process and guide it to its optimal configuration in as few iterations as possible.

## About SigOpt

With SigOpt, data scientists and machine learning engineers can build better models with less trial and error.

Machine learning models depend on hyperparameters that trade off bias/variance and other key outcomes. SigOpt provides Bayesian hyperparameter optimization using an ensemble of the latest research.

SigOpt can tune any machine learning model, including popular techniques like gradient boosting, deep neural networks, and support vector machines. SigOpt’s REST API, Python, and R libraries integrate into any existing ML workflow.

SigOpt augments your existing model training pipeline, suggesting parameter configurations to maximize any online or offline objective, such as AUC ROC, model accuracy, or revenue. You only send SigOpt your metadata, not the underlying training data or model.

SigOpt is available for a [30 day free trial](https://sigopt.com/signup), and is available [free forever for academic users](https://sigopt.com/edu).
