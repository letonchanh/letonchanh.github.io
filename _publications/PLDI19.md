---
title: "SLING: Using Dynamic Analysis to Infer Program Invariants in Separation Logic"
collection: publications
permalink: /publications/PLDI19
venue: PLDI 2019
date: 2019-10-20
authors: '<b>Ton Chanh Le</b>, Guolong Zheng, ThanhVu Nguyen'
proceedings: '<i>Proceedings of the 40th ACM SIGPLAN Conference on Programming Language Design and Implementation</i>'
confurl: https://conf.researchr.org/home/pldi-2019
paperpdf: http://letonchanh.github.io/files/pldi19.pdf
toolurl: https://github.com/letonchanh/sling
---

## Abstract
We introduce a new dynamic analysis technique to discover invariants in separation logic for heap-manipulating programs. First, we use a debugger to obtain rich program execution traces at locations of interest on sample inputs. These traces consist of heap and stack information of variables that point to dynamically allocated data structures. Next, we iteratively analyze separate memory regions related to each pointer variable and search for a formula over predefined heap predicates in separation logic to model these regions. Finally, we combine the computed formulae into an invariant that describes the shape of explored memory regions. We present SLING, a tool that implements these ideas to automatically generate invariants in separation logic at arbitrary locations in C programs, e.g., program pre and postconditions and loop invariants. Preliminary results on existing benchmarks show that SLING can efficiently generate correct and useful invariants for programs that manipulate a wide variety of complex data structures.
