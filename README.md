# K-Nearest-Neighbors-From-Scratch

## Objective
The goal of this project is to understand how K-nearest neigbhors works.<br>
The experiment is implemented using PyTorch.

## Blog Post
The post of this experiment can be found following this [link](https://consciousml.github.io/blog/knn/wine-quality/pytorch/eda/from-scratch/2020/09/13/K-Nearest-Neigbors.html).

## Wine Quality Dataset
The K-nearest neighbors is trained on physicochemical data to predict the quality of a red or white wines.<br>
This dataset contains 6497 samples and the following features:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality

## Setup
In order to install the conda environment needed to run the notebook, run the following line:
```console
conda env create --file requirements.yml
conda activate torch
```

