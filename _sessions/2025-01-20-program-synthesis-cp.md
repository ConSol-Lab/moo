---
layout: session
title: Efficient Constraint Propagation in Program Synthesis
host: Tilman Hinnerichs
host_ref: https://tilman.hinnerichs.com/
session_type: research
---

The main challenge in program synthesis is taming the large space of programs.
Since program synthesis is essentially a combinatorial search, the community has tried to leverage powerful combinatorial constraints solver, such as satisfiability solvers.
No matter the solving paradigm, all face similar challenges when encoding program spaces.
In this work, we introduce a new constraint solver tailored towards program synthesis.
We design the solver based on best practices of the constraint-solving community.
To demonstrate the benefits of using constraints for modelling program spaces and a dedicated constraint solver, we evaluate the solver on program space enumeration tasks.
We demonstrate that such constraints eliminate a significant part of program space and that investing in constraint propagation pays off.
