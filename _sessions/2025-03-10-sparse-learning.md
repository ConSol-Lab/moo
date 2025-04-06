---
layout: session
title: Sparse learning via Boolean relaxations
host: Konstantin Sidorov
host_ref: https://ksidorov.nl
session_type: paper
related_papers: s20250310
---

We are continuing exploring the applications of optimization in machine learning; our next stop is the sparse learning task, that is, learning an accurate linear model while only using few features. A textbook way of doing it is to add the L1-norm of the coefficients into the loss (also known as Lasso) and rely on its properties to _guide_ the learning into sparsity. In this session, I will present a way to _enforce_ it, expose the challenges of constructing a good relaxation, and discuss how the semidefinite programming techniques can be helpful here.
