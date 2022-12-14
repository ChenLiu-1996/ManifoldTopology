# CPSC 644 Final Project
Chen Liu (chen.liu.cl2482@yale.edu) and Danqi Liao (danqi.liao@yale.edu)

## Introduction
This folder is designated to our CPSC 644 Final Project, which serves as an initial toy study.

In this study, we will look into a simple model on simple datasets (MNIST/CIFAR-10/CIFAR-100 image classification). We will keep track of the model checkpoints along the training progress, and examine what topological features of the learned manifold best predict the quality of the manifold.

## Usage
```
python train_simple_model.py --config ./config/$CONFIG.yaml --gpu-id $AVAILABLE_GPU_ID
python comp_curvature.py --config ./config/$CONFIG.yaml
```