---
layout: post
author: "Mahdi Mohseni"
title: "Logging Datasets in Machine Learning Experiments with MLflow"
date: "2025-01-26"
description: "MLflow is widely recognized as a powerful tool for tracking machine learning (ML) experiments, enabling data scientists and ML experts to systematically log metrics, parameters, and models. However, its capabilities extend beyond these traditional use cases — MLflow can also be used to track datasets."
tags: [
    "mlflow",
    "machine_learning",
    "reproducability",
]
---

MLflow is widely recognized as a powerful tool for tracking machine learning (ML) experiments, enabling data scientists and ML experts to systematically log metrics, parameters, and models. However, its capabilities extend beyond these traditional use cases — MLflow can also be used to track datasets. Logging information about training and evaluation datasets is a critical step in enhancing the transparency and reproducibility of ML experiments. By capturing dataset details, such as versioning and splits, MLflow helps ensure that experiments can be accurately replicated and understood.

In this [Medium post](https://medium.com/@mohsenim/logging-datasets-in-machine-learning-experiments-with-mlflow-a4360d9a62da), I demonstrate how to use MLflow to track datasets alongside parameters, metrics, and other experiment artifacts. As an example, I use the Germany Cars Dataset, a publicly available dataset on Kaggle, to build a model for predicting the prices of German cars.
