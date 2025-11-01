---
layout: page
title:  Time-series Analysis
description: Techniques for analyzing time-series
img:
importance: 2
category: interests
---

Analysis of time series includes a large number research topics. In this field my research activity addresses issues related to: 
1. Anomaly and novelty detection;
2. Interpretable clustering of multi-variate time series;
3. Forecasting in irregularly sampled time series.

#### Time2Feat for interpretable clustering of multi-variate time series
Traditional systems prioritize effectiveness, efficiency, and scalability but often lack interpretability, essential for human understanding in critical scenarios.

To tackle this issue, we developed Time2Feat, an innovative machine learning system for clustering multivariate time series (MTS). Time2Feat extracts interpretable features from the time series and uses dimensionality reduction to enhance interpretability by selecting the most informative features. The system also supports semi-supervised learning, allowing domain experts to guide the clustering process with a small amount of labeled data. This approach improves both accuracy and clarity of the results. Experiments on multiple benchmarking datasets demonstrate that Time2Feat outperforms existing methods in effectiveness, interpretability, efficiency, and robustness.

Angela Bonifati, Francesco Del Buono, Francesco Guerra, Miki Lombardi, Donato Tiano:
Interpretable Clustering of Multivariate Time Series with Time2Feat. Proc. VLDB Endow. 16(12): 3994-3997 (2023)

Angela Bonifati, Francesco Del Buono, Francesco Guerra, Donato Tiano:
Time2Feat: Learning Interpretable Representations for Multivariate Time Series Clustering. Proc. VLDB Endow. 16(2): 193-201 (2022)

#### Forecasting in irregularly sampled time series.
This research led to the development and implementation of ISTF (Irregular Sequence Transformer Forecasting), a novel transformer-based model for predicting irregularly sampled multivariate time series. ISTF regularizes data on a fixed time scale, tracks missing values, and employs local and global attention to capture dependencies across time, sources, and missing data. Evaluations on real-world datasets show that ISTF achieves superior forecasting accuracy and computational efficiency compared to existing methods.

Riccardo Benassi, Francesco Del Buono, Giacomo Guiduzzi, Francesco Guerra:
Forecasting Irregularly Sampled Time Series with Transformer Encoders. ECML/PKDD (8) 2025: 201-217

