---
title: "A Resource-Based Logic for Termination and Non-termination Proofs"
collection: publications
permalink: /publications/ICFEM14
venue: ICFEM 2014
date: 2014-11-03
authors: '<b>Ton Chanh Le</b>, Cristian Gherghina, Aquinas Hobor, Wei-Ngan Chin'
proceedings: '<i>The 16th International Conference on Formal Engineering Methods</i>'
confurl: https://icfem2014.uni.lu/
paperpdf: http://letonchanh.github.io/files/icfem14.pdf
toolurl: http://loris-5.d2.comp.nus.edu.sg/hiptnt
---

## Abstract
We propose a unified logical framework for specifying and proving both termination and non-termination of various programs. Our framework is based on a resource logic which captures both upper and lower bounds on resources used by the programs. By an abstraction, we evolve this resource logic for execution length into a temporal logic with three predicates to reason about termination, non-termination or unknown. We introduce a new logical entailment system for temporal constraints and show how Hoare logic can be seamlessly used to prove termination and non-termination in our unified framework. Though this paper’s focus is on the formal foundations for a new unified framework, we also report on the usability and practicality of our approach by specifying and verifying both termination and non-termination properties for about 300 programs, collected from a variety of sources. This adds a modest 5-10% verification overhead when compared to underlying partial-correctness verification system.
