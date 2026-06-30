---
layout: page
title: Fairness, Auditability and Responsible AI
description: Methods and tools for evaluating, mitigating and auditing fairness harms in machine-learning systems.
img:
importance: 3
category: interests
---

AI systems can affect individuals, organisations and groups in different ways. DTALab studies fairness-aware machine learning methods and evaluation frameworks for building AI systems that are not only accurate, but also auditable, transparent and compatible with real-world machine-learning pipelines.

This research line focuses on three main directions:

1. **Fairness-aware model training**: methods for training accurate classifiers subject to fairness constraints, with attention to scalability, flexibility and compatibility with existing ML workflows.

2. **Fairness evaluation and benchmarking**: tools for comparing models, datasets and mitigation strategies through reproducible experimental protocols and interpretable fairness metrics.

3. **Auditability and responsible decision support**: methods that help users inspect model behaviour, understand trade-offs between accuracy and fairness, and evaluate the impact of AI systems on different groups.

A key result in this area is the work on **fairness reductions**, which addresses fair classification as a constrained optimisation problem. This approach allows fairness constraints to be added around existing machine-learning models, but can be computationally expensive. DTALab contributes algorithmic improvements based on column generation and adaptive sampling to make these approaches more scalable.

The research also includes **FairnessEval**, a framework for evaluating the fairness of machine-learning models. FairnessEval supports dataset preparation, model comparison, fairness evaluation and result presentation, helping users analyse the behaviour of fairness-aware models under different experimental settings.

This theme is closely connected to explainable AI and trustworthy decision support. Fairness cannot be treated only as a numerical metric: models should expose which trade-offs are being made, which groups are affected, and how fairness constraints influence the resulting decisions.

### Selected publications

- Andrea Baraldi, Matteo Brucato, Miroslav Dudík, Francesco Guerra, Matteo Interlandi. [Speeding up fairness reductions](https://openreview.net/forum?id=C0AdL3r1Dc). Transactions on Machine Learning Research, 2026.

- Andrea Baraldi, Matteo Brucato, Miroslav Dudík, Francesco Guerra, Matteo Interlandi. [FairnessEval: a Framework for Evaluating Fairness of Machine Learning Models](https://dblp.org/rec/conf/edbt/0002BD0I25). EDBT 2025: 1154-1157.

### Software

- [FairnessEval source code](https://github.com/softlab-unimore/fairnesseval)


