# fomo - Figuring out Machine Learning Ourselves
Fomo is an ongoing "machine learning bootcamp", based on the idea that ML is gaining traction and honestly we are collectively not super aware of the strengths and weaknesses of how this can be applied in a biological/evolutionary context. In this light, we have established of a collective monthly ML hackathon. We will meet regularly (once a month), sit down together and hash through different ML paradigms, think about how these can be applied to the kinds of data we are generating and the questions we have, and collectively work through tutorials, and maybe even do some preliminary exploratory analysis. For example, one week we might evaluate boosted regression. What are the core ideas of what this is doing? How do you achieve this in R and python? Explore how this can be applied to genetic/morphological/abundance/phylogenetic data.

* [An excellent 12-part ML Course:  Introduction to Machine Learning for Coders](https://www.fast.ai/2018/09/26/ml-launch/), from the makers of `fastai`. "Unlike many educational materials in the field, our approach is “code first” rather than “math first”."
* [Practical Machine Learning Tutorial with Python Introduction](https://pythonprogramming.net/machine-learning-tutorial-python-introduction/): An extensive ML online course based on sklearn & TensorFlow. Very, very long.

# Pre-processing/Feature Engineering

# Unsupervised methods
* [A very excellent, visual walk through of how t-SNE works](https://distill.pub/2016/misread-tsne/).

# Gradient boosting & Random forest
[TL;DR](http://fastml.com/what-is-better-gradient-boosted-trees-or-random-forest/) Gradient boosting is "better", but random forest is easier to tune, and maybe faster. Additionally, gradient boosting may have trouble when the training data is noisy.

* [Nice overview of ensemble methods](https://medium.com/@aravanshad/ensemble-methods-95533944783f)
* [A more in-depth review of the strengths and weaknesses of GBM vs RF](https://medium.com/@aravanshad/gradient-boosting-versus-random-forest-cfa3fa8f0d80)
* [A detailed and careful explanation of Gradient Boosting](https://explained.ai/gradient-boosting/index.html)

## Gradient Boosting
* [XGBoost](https://xgboost.readthedocs.io/en/latest/index.html) has nice documentation, [plenty of examples and tutorials](https://github.com/dmlc/xgboost/tree/master/demo) and R & python interfaces. It seems this is a very strong ML package, but could be more difficult to use than other options.
* [Another explanation of GBM (including a nice visual representation))[https://www.analyticsvidhya.com/blog/2016/02/complete-guide-parameter-tuning-gradient-boosting-gbm-python/]. Also goes into extensive depth explaining all the parameters.

# Deep learning
* Zhou et al 2018 [A primer on deep learning in genomics](https://sci-hub.tw/https://www.nature.com/articles/s41588-018-0295-5)

## Deep learning frameworks
* [fastai](https://docs.fast.ai/index.html): Python wrapper around pytorch focused on making construction and training of NN fast and easy. Good documentation and examples (focused on vision, text classficiation, and tabular datasets).
* [keras](https://keras.io/), a high level python deep learning library. [Tons of excellent examples in the repo](https://github.com/keras-team/keras/tree/master/examples).

# Time series
* [Time Series Prediction Using LSTM Deep Neural Networks](https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks) - This person actually implements the LSTM neural network from scratch! Cool for learning about the nuts and bolts.

# Other ML-like applications (with special attention to biodiversity analysis)
* [Ellis et al 2011 - Gradient forests: calculating importance gradients
 on physical predictors](https://www.jstor.org/stable/pdf/23144030.pdf)
* More on gradient forests: [Fitzpatrick et al 2014 - Ecological genomics meets community-level modelling of
biodiversity: mapping the genomic landscape of current and
future environmental adaptation](https://sci-hub.tw/https://onlinelibrary.wiley.com/doi/pdf/10.1111/ele.12376)
