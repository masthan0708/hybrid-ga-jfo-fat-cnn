# Hybrid GA-JFO-FAT Optimization for CNN Hyperparameter Tuning

A hybrid metaheuristic optimization framework for improving the performance of a Modified Convolutional Neural Network (CNN) on the CIFAR-10 image classification dataset.

## 📌 Overview

Hyperparameter optimization is an important part of developing effective deep learning models. This project explores a hybrid optimization framework that combines three metaheuristic optimization techniques:

- Genetic Algorithm (GA)
- Jellyfish Optimization (JFO)
- Feedback Artificial Tree (FAT)

The proposed approach is applied to a Modified Convolutional Neural Network for image classification on the CIFAR-10 dataset.

The optimization process combines the strengths of evolutionary optimization, swarm-based optimization, and feedback-based refinement to improve CNN performance.

## 🎯 Objectives

The main objectives of this project are:

- Develop a Modified CNN for CIFAR-10 image classification.
- Investigate metaheuristic optimization for CNN optimization.
- Use Genetic Algorithm (GA) for hyperparameter optimization.
- Apply Jellyfish Optimization (JFO) for further model optimization.
- Use Feedback Artificial Tree (FAT) for adaptive refinement.
- Compare the optimized approaches with a baseline CNN.
- Evaluate the resulting models using classification performance metrics.

## 🧠 Methodology

The proposed optimization framework follows a sequential optimization process:

```text
                  CIFAR-10 Dataset
                         │
                         ▼
                  Modified CNN
                         │
                         ▼
              Genetic Algorithm (GA)
               Hyperparameter Search
                         │
                         ▼
             Jellyfish Optimization
                    (JFO)
                         │
                         ▼
            Feedback Artificial Tree
                    (FAT)
                         │
                         ▼
                 Optimized CNN
                         │
                         ▼
                 Classification