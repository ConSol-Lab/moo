---
layout: session
title: Conflict Analysis Based on Cutting Planes for CP
host: Robbin Baauw
session_type: research
---

This paper introduces a novel constraint learning mechanism for Constraint Programming (CP) solvers that integrates cutting planes reasoning into the conflict analysis procedure. Drawing inspiration from Lazy Clause Generation (LCG), our approach, named Lazy Linear Generation (LLG), can generate linear integer inequalities to prune to search space, rather than propositional clauses as in LCG. This combines the strengths of constraint programming (strong propagation through global constraints) with cutting planes reasoning. We present linear constraint explanations for arithmetic constraints (not-equal, absolute value, maximum, integer multiplication, truncating division) and the element constraint. An experimental evaluation on 952 MiniZinc Challenge instances shows that our approach greatly reduces the number of conflicts compared to LCG. The number of conflicts is also reduced compared to decomposing to linear inequalities, due to the stronger propagation in the CP solver. While more engineering efforts are needed to fully exploit the potential, our analysis and prototype implementation shows promising results and are an important step towards a new paradigm to make constraint programming solvers more effective.
