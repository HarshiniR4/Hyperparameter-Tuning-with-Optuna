# Hyperparameter-Tuning-with-Optuna
Using Optuna to tune the hyperparamters and identify if SGD or Adam is a better hyperparameter for threee datasets:
- **MNIST Dataset**
- **CIFAR10 Dataset**
- **IMDB Dataset**

## Process

- Pre-processing the CIFAR10 Dataset
- Implementing a custom Callback function that will help enable a recursive learning rate
- Train dataset with Adam and SGD as optimiser
- Utilising Optuna to identify which optimiser is better in performance
