# Hyperparameter-Optimization-BO-with-High-deimensional-DNN

A implementation of Hyperparameter-Optimization-BO-with-High-deimensional-DNN (HDBO)

This model is developed from the https://github.com/automl/RoBO/tree/master

# How to install project(Colab)

```
!sudo apt-get install libeigen3-dev swig  

!git clone https://github.com/dream233/Hyperparameter-Optimization-BO-with-High-deimensional-DNN

%cd Hyperparameter-Optimization-BO-with-High-deimensional-DNN/

!pip install -e .

!pip install git+https://github.com/automl/HPOlib1.5

!pip install ConfigSpace

!pip install openml
```

# Common problem

ImportError: No module named sklearn.cross_validation

Just change cross_validation to model_selection will fix it.
