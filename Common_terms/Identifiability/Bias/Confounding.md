Confounding
============

Motivation
==========
Confounding, in its original English definition, stands for "mixing up", "thorwing (a person) into confusion or perplexity", or cause "bafflement and frutsration" ([confound](https://www.merriam-webster.com/dictionary/confound)). It should not come as a surprise then, that this term has been adapted by statisticians and researchers in causal inference to define spurrious associations, lurking variables that might "confuse" a researcher as they try to explain a specific effect of interest. Ronald Fisher, in his 1935 book "The Design of Experiments" to refer to sources of error in an experimental design. Judea Pearl has a slightly different outlook on the term, in his explicit pursuit of *causal* effect. 

Definition
==========
"If we undertake to estimate the effect of one variable (X) on another (Y) by examining the statistical association between the two, we ought to ensure that the association is not produced by factors other than the effect under study", Pearl writes in the introduction to his 1998 paper [Why there is No Statistical Test for Confounding, Why Many Think there is, and Why They Are Almost Right](https://ftp.cs.ucla.edu/pub/stat_ser/R256.pdf)."The presence of spurious association, due for example to the influence of extraneuos variables, is called _confounding_ as it tends to confound our reading and to bias our estimate of the effect studies". 

Sander Greenland points out, in his [Encyclopedia of Epidemiology entry on confounding](https://sk.sagepub.com/reference/epidemiology/n89.xml), points out that there are at least definitions to confounding, differing between causal inference, statistics and experimental-design literature. While the three are closely related (the statistical use focuses on Simpson's Paradox, in experimental-design references it is used to refer to inseperability of a main effect of interest and interactions), their emphasis is slightly different.

While the threat of confounding is potentially the reason why randomized controlled experiments (RCTs) became the gold standrad for scientific enquiry of cause and effect, causal inference aims to make use of data that was collected as purely observational data to still be able to estimate causal effect of interest. It does so through a systematic study of the data generation process, through which we can judge which variables to include in our analysis such that confounding can be *blocked*. For more on adjustments that enable us to estimate causal effects from observational data via blocking of confounding, see [Backdoor criterion](https://github.com/limorigu/causal-inf-handbook/blob/master/Common_terms/Identifiability/Do_calculus/Backdoor.md), [Frontdoor criterion](https://github.com/limorigu/causal-inf-handbook/blob/master/Common_terms/Identifiability/Do_calculus/Frontdoor.md). For more on types of associations between variables in a causal graph, confounders, and how to systematically judge the data generation process, see [d-separation](https://github.com/limorigu/causal-inf-handbook/blob/master/Common_terms/Identifiability/Do_calculus/d-separation.md).

Further Reading
====
1. [Judea Pearl's Why there is No Statistical Test for Confounding, Why Many Think there is, and Why They Are Almost Right](https://ftp.cs.ucla.edu/pub/stat_ser/R256.pdf), later embeded in Chapter 6 of [Causality 2nd edition](http://bayes.cs.ucla.edu/BOOK-2K/), as section 6.2
2. [Sander Greenland entry in Encyclopedia of Epidemiology](https://sk.sagepub.com/reference/epidemiology/n89.xml)
3. [Confounding on Wikipedia](https://en.wikipedia.org/wiki/Confounding)