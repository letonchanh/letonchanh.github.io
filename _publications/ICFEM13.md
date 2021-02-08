---
title: "A Proof Slicing Framework for Program Verification"
collection: publications
permalink: /publications/ICFEM13
venue: ICFEM 2013
date: 2014-10-29
authors: '<b>Ton Chanh Le</b>, Cristian Gherghina, Razvan Voicu, Wei-Ngan Chin'
proceedings: '<i>The 15th International Conference on Formal Engineering Methods</i>'
confurl: https://www.cs.auckland.ac.nz/research/conferences/icfem2013/index.php
paperpdf: http://letonchanh.github.io/files/icfem13.pdf
---

## Abstract
In the context of program verification, we propose a formal framework for proof slicing that can aggressively reduce the size of proof obligations as a means of performance improvement. In particular, each large proof obligation may be broken down into smaller proofs, for which the overall processing cost can be greatly reduced, and be even more effective under proof caching. Our proposal is built on top of existing automatic provers, including the state-of-the-art prover Z3, and can also be viewed as a re-engineering effort in proof decomposition that attempts to avoid large-sized proofs for which these provers may be particularly inefficient. In our approach, we first develop a calculus that formalizes a complete proof slicing procedure, which is followed by the development of an aggressive proof slicing method. Retaining completeness is important, and thus in our experiments the complete method serves as a backup for the cases when the aggressive procedure fails. The foundations of the aggressive slicing procedure are based on a novel lightweight annotation scheme that captures weak links between sub-formulas of a proof obligation; the annotations can be inferred automatically in practice, and thus both methods are fully automated.
