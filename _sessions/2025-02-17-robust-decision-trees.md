---
layout: session
title: Robust Decision Trees
host: Daniël Vos
host_ref: https://daniel-vos.github.io/
session_type: research
related_papers: s20250217
---

Decision trees are a popular choice of interpretable model, but just like neural networks, they suffer from adversarial examples: adversarial perturbations that result in misclassifications. Existing algorithms for fitting decision
trees that are robust against adversarial examples are greedy heuristics and, therefore, lack approximation guarantees. We propose Robust Optimal Classification Trees (ROCT), a collection of methods to train decision trees that are optimally robust against
user-specified attack models. We show that the min-max optimization problem that arises in adversarial learning can be solved using a single minimization formulation for decision trees with 0-1 loss. We propose such formulations in Mixed-Integer Linear Programming
and Maximum Satisfiability, which widely available solvers can optimize. We also present a method that uses bipartite matching to compute robust leaf labels in polynomial time and can be used to determine the upper bound on adversarial accuracy for any model.
