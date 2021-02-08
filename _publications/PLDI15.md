---
title: "Termination and Non-termination Specification Inference"
collection: publications
permalink: /publications/PLDI15
venue: PLDI 2015
date: 2015-06-13
authors: '<b>Ton Chanh Le</b>, Guolong Zheng, ThanhVu Nguyen'
proceedings: '<i>The 36th annual ACM SIGPLAN conference on Programming Language Design and Implementation</i>'
confurl: https://pldi15.sigplan.org/
paperpdf: http://letonchanh.github.io/files/pldi15.pdf
toolurl: http://loris-5.d2.comp.nus.edu.sg/hiptnt/plus
---

## Abstract
Techniques for proving termination and non-termination of imperative programs are usually considered as orthogonal mechanisms. In this paper, we propose a novel mechanism that analyzes and proves both program termination and non-termination at the same time. We first introduce the concept of second-order termination constraints and accumulate a set of relational assumptions on them via a Hoare-style verification. We then solve these assumptions with case analysis to determine the (conditional) termination and non- termination scenarios expressed in some specification logic form. In contrast to current approaches, our technique can construct a summary of terminating and non-terminating behaviors for each method. This enables modularity and reuse for our termination and non-termination proving processes. We have tested our tool on sample programs from a recent termination competition, and compared favorably against state-of-the-art termination analyzers.
