# Machine Learning Models with Django


- it stores information about requests sent to the ML models, this can be used later for model testing and audit.
- it has tests for ML code and server code,
- it can run A/B tests between different versions of ML models.

## The code structure

In the `research` directory there are:

- code for training machine learning models on Adult-Income dataset [link](https://github.com/ASHWANIKY2308/INCOME_PROJ_ML/blob/master/research/train_income_classifier.ipynb)
- code for simulating A/B tests [link](https://github.com/ASHWANIKY2308/INCOME_PROJ_ML/blob/master/research/ab_test.ipynb)

In the `backend` directory there is Django application.

In the `docker` directory there are dockerfiles for running the service in the container.


