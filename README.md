# Stockprice_prediction_with_sklearn

Use scikit learn, keras and tensor flow for some basic predictions.

Please clone the git repository the usual way by running

```
$ git clone https://github.com/stefan-stein/Stockprice_prediction_with_sklearn.git
```

Then open up the jupyter notebook to see the sample code.

**Disclaimer:** These models are not fit to be used for actual stock price prediction. This notebook is more of a showcase of the various regression models available in `scikit-learn` and `tensorflow`, as well as exploring how to best visualize the predictions.

# Models used in this notebook

In this notebook we explore the performance of three regression models:

* Ridge regression from [`scikit-learn`](https://scikit-learn.org/stable/modules/linear_model.html), i.e. `sklearn.linear_model.Ridge`
* Gradient boosting from `scikit-learn`, i.e. `sklearn.ensemble.GradientBoostingRegressor`
* And finally an LSTM neural network using `keras` with `tensorflow` backend.
