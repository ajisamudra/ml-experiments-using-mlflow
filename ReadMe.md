# Machine Learning Experimentation solving MNIST
---

## Objective
In this notebook, we will learn to experiment solving [MNIST](http://yann.lecun.com/exdb/mnist/) dataset using several different learning algorithm e.g. Logistic Regression, Random Forest, Multi Layer Perceptron (MLP), and Convolutional Neural Network (CNN) while tracking the experiment using [MLfow](https://www.mlflow.org/docs/latest/tracking.html)

## Problem
Given 28x28 pixels of handwritten digit, predict the number (0-9), hence this is multi-class classification problem.

## Evaluation Metrics
- Accuracy
- F1 score
- Precision
- Recall
- Time taken for training
- Time taken for predicting

---

## Environment
This notebook run using python 3.7. I use Anaconda to set the environment.

```bash
conda create --name new_environment python=3.7 # create new environment
conda activate new_environment # activate the env
pip install -r requirements.txt # install packages in requirements.txt
```

## 
