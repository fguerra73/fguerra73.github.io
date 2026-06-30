---
layout: page
title: Financial AI and Decision Support
description: Reproducible benchmarking and portfolio-oriented evaluation for stock market prediction models.
img:
importance: 4
category: interests
---

Financial AI systems are increasingly used to support prediction, risk analysis and portfolio-oriented decision making. DTALab studies financial AI with a focus on reproducibility, heterogeneous data integration, fair comparison of models and evaluation protocols that connect predictive performance to downstream financial decisions.

The goal is not only to develop predictive models, but to understand how different modelling assumptions, data sources, task formulations and evaluation metrics affect the behaviour of financial prediction pipelines.

This research line focuses on four main directions:

1. **Heterogeneous financial data integration**: construction of datasets that combine market microstructure indicators, macroeconomic variables, relational information among firms, sector and industry metadata, corporate governance and ownership relations, and financial news.

2. **Stock market prediction tasks**: unified evaluation of classification, regression and ranking models for financial prediction, covering price movement prediction, return forecasting and cross-sectional asset ranking.

3. **Portfolio-oriented evaluation**: analysis of whether predictive signals translate into useful portfolio decisions through long-only, long-short and quintile-based strategies.

4. **Reproducible benchmarking**: standardization of preprocessing, temporal alignment, task formulation, model execution and evaluation metrics to make results comparable across models, markets and investment horizons.

A key result in this area is **FinBench**, a benchmarking framework for stock market prediction and portfolio allocation. FinBench integrates heterogeneous financial signals and evaluates models both at the prediction-task level and at the portfolio level, under consistent experimental settings.

FinBench supports multiple investment universes, including European and US equity markets, and evaluates models across different liquidity profiles, market structures and prediction horizons. Its architecture is organized into three main components: data construction, model execution, and prediction/portfolio evaluation.

This research contributes to trustworthy financial AI by making financial prediction pipelines more transparent, reproducible and comparable. It supports analysts and researchers in understanding whether model performance is driven by the model itself, by data construction choices, by preprocessing, or by the selected evaluation protocol.

### Selected publication

- Sara Pederzoli, Marta Santacroce, Francesco Guerra, Marco Bergianti, Francesco Del Buono. [FinBench: A Benchmarking Framework for Stock Market Prediction and Portfolio Allocation](https://doi.org/10.1145/3770855.3817595). KDD 2026, Resource Track, 12 pages.

### Software

- [FinBench source code](https://github.com/softlab-unimore/finbench)


