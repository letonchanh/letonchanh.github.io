---
title: "HipTNT+: A Termination and Non-termination Analyzer by Second-Order Abduction"
collection: publications
permalink: /publications/SVCOMP17
venue: "SV-COMP 2017"
date: 2017-04-24
authors: '<b>Ton Chanh Le</b>, Quang-Trung Ta, Wei-Ngan Chin'
proceedings: '<i>The 23rd International Conference on Tools and Algorithms for the Construction and Analysis of Systems: SV-COMP (SV-COMP@TACAS)</i>'
confurl: https://sv-comp.sosy-lab.org/2017/
paperpdf: http://letonchanh.github.io/files/svcomp17.pdf
toolurl: http://loris-5.d2.comp.nus.edu.sg/hiptnt/plus
---

## Abstract
HipTNT+ is a modular termination and non-termination analyzer for imperative programs. For each given method, the analyzer first annotates it with an initial specification with second-order unknown predicates and then incrementally derives richer known specifications with case analysis. Subsequently, the final inference result indicates either (conditional) termination, non-termination, or unknown. During the proving process, new conditions for the case analysis are abductively inferred from the failure of both termination and non-termination proof, which aim to separate the terminating and non-terminating behaviors for each method. This paper introduces the verification approach and the structure of HipTNT+, and instructs how to set up and use the system.
