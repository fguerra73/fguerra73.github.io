---
layout: page
title: Data Integration and Explainable Entity Matching
description: Methods for matching, linking, cleaning and explaining heterogeneous records in data integration pipelines.
img:
importance: 2
category: interests
---

Entity Matching (EM) aims to identify records that refer to the same real-world entity across heterogeneous data sources. It is a central task in data integration, data cleaning, deduplication and the construction of reliable data-intensive applications.

DTALab studies Entity Matching not only as a prediction task, but as an interpretable and auditable component of data integration pipelines. The goal is to design methods that can decide whether two records match, explain why they match or do not match, and support users in understanding the evidence behind model decisions.

The research line focuses on three main directions:

1. **Explainable Entity Matching**: methods that explain the behaviour of Machine Learning and Deep Learning models for EM, including post-hoc explanation techniques and model-aware diagnostics.

2. **Intrinsically interpretable EM models**: approaches that produce matching decisions through meaningful intermediate representations, such as decision units and interpretable feature spaces.

3. **Evaluation and analysis of neural EM models**: studies of how BERT-based and Transformer-based models perform Entity Matching, which components drive their predictions, and how their decisions can be inspected.

Recent work in this area includes **Landmark Explanation**, an explainer designed for Entity Matching models; **WYM**, an intrinsically interpretable EM system based on decision units; and **CREW**, a cluster-based explanation method that groups words according to semantic similarity, dataset structure and their importance for the matching decision.

This research contributes to trustworthy data integration pipelines where matching decisions must be accurate, understandable and usable by domain experts.

### Selected publications

- Riccardo Benassi, Francesco Guerra, Matteo Paganelli, Donato Tiano. [Explaining Entity Matching with Clusters of Words](https://dblp.org/rec/conf/icde/Benassi0PT24). ICDE 2024: 2325-2337.

- Riccardo Benassi, Michele Luca Contalbo, Francesco Del Buono, Francesco Guerra, Giacomo Guiduzzi, Matteo Paganelli, Sara Pederzoli, Donato Tiano, Maurizio Vincini. [Explaining Entity Matching Models with CREW](https://dblp.org/rec/conf/sebd/BenassiCBGGPPTV25). SEBD 2025: 570-579.

- Matteo Paganelli, Donato Tiano, Francesco Del Buono, Andrea Baraldi, Riccardo Benassi, Giacomo Guiduzzi, Francesco Guerra. [How Transformers Are Revolutionizing Entity Matching](https://dblp.org/rec/conf/sebd/PaganelliTB0BG024). SEBD 2024: 662-670.

- Matteo Paganelli, Donato Tiano, Francesco Guerra. [A multi-facet analysis of BERT-based entity matching models](https://dblp.org/rec/journals/vldb/PaganelliTG24). The VLDB Journal 33(4): 1039-1064, 2024.

- Andrea Baraldi, Francesco Del Buono, Francesco Guerra, Matteo Paganelli, Maurizio Vincini. [An Intrinsically Interpretable Entity Matching System](https://dblp.org/rec/conf/edbt/0002B0PV23). EDBT 2023: 645-657.

- Matteo Paganelli, Francesco Del Buono, Andrea Baraldi, Francesco Guerra. [Analyzing How BERT Performs Entity Matching](https://dblp.org/rec/journals/pvldb/PaganelliBBG22). Proceedings of the VLDB Endowment 15(8): 1726-1738, 2022.

- Andrea Baraldi, Francesco Del Buono, Matteo Paganelli, Francesco Guerra. [Landmark Explanation: An Explainer for Entity Matching Models](https://dblp.org/rec/conf/cikm/BaraldiBP021). CIKM 2021: 4680-4684.

- Andrea Baraldi, Francesco Del Buono, Matteo Paganelli, Francesco Guerra. [Using Landmarks for Explaining Entity Matching Models](https://dblp.org/rec/conf/edbt/BaraldiBP021). EDBT 2021: 451-456.

- Matteo Paganelli, Francesco Del Buono, Marco Pevarello, Francesco Guerra, Maurizio Vincini. [Automated Machine Learning for Entity Matching Tasks](https://dblp.org/rec/conf/edbt/PaganelliBP0V21). EDBT 2021: 325-330.

- Matteo Paganelli, Francesco Del Buono, Francesco Guerra, Nicola Ferro. Evaluating the integration of datasets. SAC 2022: 347-356.



