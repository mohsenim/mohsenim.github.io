---
layout: post
author: "Mahdi Mohseni"
title: "Time Series Forecasting - Quantile Forecasting - Quantile Loss"
date: 2025-02-11
tags: ["time_Series_Forecasting", "quantile_regression", "loss_function", "quantile_loss", "pinball_loss"]
description: "Traditional forecasting treats over- and under-predictions equally, but in real-world scenarios like financial markets, the costs can differ significantly. Quantile forecasting addresses this by estimating confidence intervals, offering a nuanced view of uncertainty. In my latest post, I explore how this method works and cover its advantages."
draft: false
---

The most common approach in time series regression analysis is symmetric modeling, where the objective is to predict the mean of the dependent variable using the least squares method. In this approach, over-predictions and under-predictions are treated equally. However, analysis can also be asymmetric, where the costs of over-prediction and under-prediction differ. This is particularly important in many real-world scenarios where over-estimation or under-estimation can result in significant losses. For example, in forecasting financial markets, any under-estimation of risks can lead to substantial financial damage.

Furthermore, an unbiased estimation of the dependent variable does not provide information about the uncertainty in the prediction or the accuracy of the forecast. 

Quantile forecasting addresses these limitations by offering a more nuanced view of the prediction intervals and the associated risks. It estimats an interval for the dependent variable. In other words, it determines a confidence interval for its prediction based on the conditional distribution of the dependent variable.

[Read more ...](https://medium.com/@mohsenim/time-series-forecasting-quantile-forecasting-quantile-loss-316dd071a0ca)
