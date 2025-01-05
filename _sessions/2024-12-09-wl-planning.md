---
layout: session
title: "Weisfeiler-Leman + Classical Machine Learning to guide search in planning"
host: Koos van der Linden
session_type: paper
related_papers: s20241209
---

We will look at using 'simple' ML models on graph kernels as a heuristic for search in planning instead of complex GNNs or deep learning (DL) approaches. This approach addresses three shortcomings of DL and GNN: (1) too many hyperparameters, (2) lack of interpretability, and (3) data and computationally intensive. The SVM approach of the paper mentioned below trains in 15 seconds rather than hours, requires almost no hyperparameter tuning, and uses two orders of magnitude fewer parameters. They claim that this is the first learning-based approach that outperforms the human crafted 'fast-forward' heuristic. To understand their approach, we are going to review the Weisfeiler-Leman algorithm to detect graph isomorphism and its relation to GNNs with message passing.
