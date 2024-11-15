---
layout: session
title: "Column Elimination: An Iterative Approach to Solving Integer Programs"
host: Anthony Karahalios
host_ref: https://amkarahalios.github.io/
session_type: research
---

Column elimination is an exact algorithm to solve discrete optimization problems via a 'column' formulation in which variables represent a combinatorial structure such as a machine schedule or truck route.  Column elimination works with a relaxed set of columns, from which infeasible ones are iteratively eliminated.  As the total number of columns can typically be exponentially large, we use relaxed decision diagrams to compactly represent and manipulate the set of columns.  In this talk, we provide an introduction to the column elimination method and present recent algorithmic improvements resulting in competitive performance on large-scale vehicle routing problems. Specifically, our approach closes a large vehicle routing benchmark instance with 1,000 locations for the first time.