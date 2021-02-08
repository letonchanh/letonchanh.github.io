---
title: "Automated Mutual Induction Proof in Separation Logic"
collection: publications
permalink: /publications/FAC19
venue: FAC 2019
date: 2019-10-11
authors: 'Quang-Trung Ta, <b>Ton Chanh Le</b>, Siau-Cheng Khoo, Wei-Ngan Chin'
proceedings: '<i>Formal Aspects of Computing 31(2)</i>'
paperpdf: http://letonchanh.github.io/files/fac19.pdf
confurl: https://doi.org/10.1007/s00165-018-0471-5
toolurl: https://songbird-prover.github.io/mutual-induction/index.html
---

## Abstract
We present a deductive proof system to automatically prove separation logic entailments by mathematical induction. Our technique is called the mutual induction proof. It is an instance of the well-founded induction, a.k.a., Noetherian induction. More specifically, we propose a novel induction principle based on a well-founded relation of separation logic models. We implement this principle explicitly as inference rules so that it can be easily integrated into a deductive proof system. Our induction principle allows a goal entailment and other entailments derived during the proof search to be used as hypotheses to mutually prove each other. This feature increases the success chance of proving the goal entailment. We have implemented this mutual induction proof technique in a prototype prover and evaluated it on two entailment benchmarks collected from the literature as well as a synthetic benchmark. The experimental results are promising since our prover can prove most of the valid entailments in these benchmarks, and achieves a better performance than other state-of-the-art separation logic provers.
