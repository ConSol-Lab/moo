---
layout: session
title: Exploiting a convex hull trick for finding optimal binary features
host: Koos van der Linden
session_type: paper
related_papers: s20250428
---

An important subproblem in supervised tasks such as decision tree induction and subgroup discovery is finding an interesting binary feature (such as a node split or a subgroup refinement) based on a numeric or nominal attribute, with respect to some discrete or continuous target variable. Often one is faced with a trade-off between the expressiveness of such features on the one hand and the ability to efficiently traverse the feature search space on the other hand. In this article, we present efficient algorithms to mine binary features that optimize a given convex quality measure. For numeric attributes, we propose an algorithm that finds an optimal interval, whereas for nominal attributes, we give an algorithm that finds an optimal value set. By restricting the search to features that lie on a convex hull in a coverage space, we can significantly reduce computation time. We present some general theoretical results on the cardinality of convex hulls in coverage spaces of arbitrary dimensions and perform a complexity analysis of our algorithms. In the important case of a binary target, we show that these algorithms have linear runtime in the number of examples. We further provide algorithms for additive quality measures, which have linear runtime regardless of the target type. Additive measures are particularly relevant to feature discovery in subgroup discovery. Our algorithms are shown to perform well through experimentation and furthermore provide additional expressive power leading to higher-quality results.
