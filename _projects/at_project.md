---
layout: page
title: Interpretable Time-series Analysis
description: Methods for interpretable clustering, novelty detection, self-supervised learning and forecasting of multivariate time series.
img:
importance: 2
category: interests
---

Time-series analysis is a central task in many data-intensive domains, including industrial monitoring, environmental sensing, geoscience, finance and decision-support systems. DTALab studies time-series methods with a specific focus on interpretability, robustness and applicability to complex real-world data.

The research line focuses on four main directions:

1. **Interpretable clustering of multivariate time series**: methods that extract meaningful features from multivariate signals and produce clusters that can be inspected and understood by domain experts.

2. **Novelty and anomaly detection**: techniques for identifying new or abnormal operating conditions in industrial and monitoring scenarios, with attention to the explanation of which signals contribute to the detected change.

3. **Forecasting of irregularly sampled time series**: transformer-based models for forecasting multivariate time series affected by irregular sampling, missing values and heterogeneous temporal dependencies.

4. **Self-supervised learning for time-series forecasting**: data-centric methods that exploit decomposed representations of time series to improve forecasting models in label-scarce or complex multivariate settings.

A key result in this area is **Time2Feat**, an end-to-end system for clustering multivariate time series through interpretable inter-signal and intra-signal features. Time2Feat applies feature selection and dimensionality reduction to retain the most informative features and improve the interpretability of the resulting clusters.

The forecasting line includes **ISTF** and **TED4STL**. ISTF addresses forecasting of irregularly sampled multivariate time series with transformer encoders, combining temporal regularization, missing-value tracking and local/global attention mechanisms. TED4STL introduces a trend-error decomposition pipeline for self-supervised time-series learning, decomposing each series into trend and error components and evaluating whether these representations improve multivariate forecasting.

The research also includes domain-oriented applications. In industrial monitoring, autoencoder-based models are studied for novelty detection and system health monitoring. In geoscience, interpretable clustering methods have been applied to PS-InSAR time series for ground deformation detection.

This research contributes to trustworthy time-series analytics where models must not only produce accurate predictions, clusters or anomaly scores, but also expose patterns, signals and temporal behaviours that can be validated by experts.

### Selected publications

- Sara Pederzoli, Francesco Del Buono, Maurizio Vincini, Francesco Guerra. [Trend-Error Decomposition for Self-Supervised Time Series Learning in Multivariate Forecasting Task](https://doi.org/10.1109/ACCESS.2026.3653488). IEEE Access 14: 8618-8631, 2026.

- Riccardo Benassi, Francesco Del Buono, Giacomo Guiduzzi, Francesco Guerra. [Forecasting Irregularly Sampled Time Series with Transformer Encoders](https://link.springer.com/chapter/10.1007/978-3-662-72243-5_12). ECML PKDD 2025, LNCS 16020: 201-217, 2026.

- Claudia Masciulli, Giacomo Guiduzzi, Donato Tiano, Marta Zocchi, Francesco Guerra, Paolo Mazzanti, Gabriele Scarascia Mugnozza. [Interpretable clustering of PS-InSAR time series for ground deformation detection](https://doi.org/10.1016/j.cageo.2025.105959). Computers & Geosciences 203: 105959, 2025.

- Angela Bonifati, Francesco Del Buono, Francesco Guerra, Miki Lombardi, Donato Tiano. [Interpretable Clustering of Multivariate Time Series with Time2Feat](https://www.vldb.org/pvldb/vol16/p3994-guerra.pdf). Proceedings of the VLDB Endowment 16(12): 3994-3997, 2023.

- Angela Bonifati, Francesco Del Buono, Francesco Guerra, Donato Tiano. [Time2Feat: Learning Interpretable Representations for Multivariate Time Series Clustering](https://dblp.org/rec/journals/pvldb/BonifatiB0T22). Proceedings of the VLDB Endowment 16(2): 193-201, 2022.

- Francesco Del Buono, Francesca Calabrese, Andrea Baraldi, Matteo Paganelli, Francesco Guerra. [Novelty Detection with Autoencoders for System Health Monitoring in Industrial Environments](https://doi.org/10.3390/app12104931). Applied Sciences 12(10): 4931, 2022.

### Software

- [TED4STL source code](https://github.com/softlab-unimore/TED4STL)
- [ISTF source code](https://github.com/softlab-unimore/ISTF)
- [Time2Feat source code](https://github.com/softlab-unimore/time2feat)
- [PS-InSAR interpretable clustering source code](https://github.com/giacomoguiduzzi/Interpretable_PS-InSAR_Clustering)

For a complete list of publications, see the [DBLP profile](https://dblp.org/pid/g/FrancescoGuerra.html) and the [UNI-FIND profile](https://unimore.unifind.cineca.it/get/person/090294).

