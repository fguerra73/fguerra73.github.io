---
layout: page
title: Semantic Robustness and Red-teaming
description: Methods for testing the robustness of NLP and LLM systems against adversarial triggers, semantic perturbations and manipulative formulations.
img:
importance: 3
category: interests
---

Language-based AI systems can be highly sensitive to small changes in wording, prompt formulation or contextual framing. DTALab studies semantic robustness and red-teaming methods for testing how NLP models, fact-checking systems, RAG pipelines and LLM-based components behave under adversarial or semantically subtle perturbations.

The goal is to move beyond standard accuracy evaluation and understand when a model changes its prediction for the wrong reasons: because of trigger words, manipulative formulations, biased associations, semantic drift or evidence poisoning.

This research line focuses on four main directions:

1. **Adversarial testing of textual models**: methods for identifying linguistic patterns, triggers and perturbations that can alter model predictions.

2. **Semantic-preserving perturbations**: generation and evaluation of textual variations that preserve the meaning of the original input while exposing model vulnerabilities.

3. **Robustness auditing of fact-checking and RAG systems**: analysis of how verification and retrieval-based systems react to misleading wording, irrelevant evidence, contradictory evidence or poisoned contexts.

4. **Bias and vulnerability diagnosis**: methods for understanding whether model decisions depend on robust semantic evidence or on unstable lexical, prompt-level or dataset-specific artifacts.

A key result in this area is the study of universal adversarial triggers for fact verification. The work investigates how trigger expressions can induce prediction changes in fact-checking models and how LLM-based perturb-and-verify procedures can help preserve semantic validity while testing model robustness.

This theme supports the development of trustworthy language-based AI systems. In applications such as information integrity, compliance, education, document analysis and decision support, models should not only produce accurate outputs, but also remain stable under reasonable reformulations and resistant to manipulative or adversarial inputs.



### Keywords

Semantic robustness; adversarial testing; semantic red-teaming; universal adversarial triggers; fact verification; RAG auditing; prompt perturbation; bias diagnosis.


