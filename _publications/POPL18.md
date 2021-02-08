---
title: "Automated Lemma Synthesis in Symbolic-Heap Separation Logic"
collection: publications
permalink: /publications/POPL18
venue: POPL 2018
date: 2018-01-07
authors: 'Quang-Trung Ta, <b>Ton Chanh Le</b>, Siau-Cheng Khoo, Wei-Ngan Chin'
proceedings: '<i>Proceedings of the ACM on Programming Languages, Volume 2, Issue POPL</i>'
confurl: https://popl18.sigplan.org/
paperpdf: http://letonchanh.github.io/files/popl18.pdf
toolurl: https://songbird-prover.github.io/lemma-synthesis/index.html
---

## Abstract
The symbolic-heap fragment of separation logic has been actively developed and advocated for verifying the memory-safety property of computer programs. At present, one of its biggest challenges is to effectively prove entailments containing inductive heap predicates. These entailments are usually proof obligations generated when verifying programs that manipulate complex data structures like linked lists, trees, or graphs. To assist in proving such entailments, this paper introduces a lemma synthesis framework, which automatically discovers lemmas to serve as eureka steps in the proofs. Mathematical induction and template-based constraint solving are two pillars of our framework. To derive the supporting lemmas for a given entailment, the framework firstly identifies possible lemma templates from the entailment's heap structure. It then sets up unknown relations among each template's variables and conducts structural induction proof to generate constraints about these relations. Finally, it solves the constraints to find out actual definitions of the unknown relations, thus discovers the lemmas. We have integrated this framework into a prototype prover and have experimented it on various entailment benchmarks. The experimental results show that our lemma-synthesis-assisted prover can prove many entailments that could not be handled by existing techniques. This new proposal opens up more opportunities to automatically reason with complex inductive heap predicates.
