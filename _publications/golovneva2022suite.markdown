---
layout: publication
title: 'ROSCOE: A Suite Of Metrics For Scoring Step-by-step Reasoning'
authors: Olga Golovneva et al.
conference: Arxiv
year: 2022
citations: 23
bibkey: golovneva2022suite
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.07919'}]
tags: [Interpretability and Explainability, Prompting, Language Modeling]
---
Large language models show improved downstream task performance when prompted
to generate step-by-step reasoning to justify their final answers. These
reasoning steps greatly improve model interpretability and verification, but
objectively studying their correctness (independent of the final answer) is
difficult without reliable methods for automatic evaluation. We simply do not
know how often the stated reasoning steps actually support the final end task
predictions. In this work, we present ROSCOE, a suite of interpretable,
unsupervised automatic scores that improve and extend previous text generation
evaluation metrics. To evaluate ROSCOE against baseline metrics, we design a
typology of reasoning errors and collect synthetic and human evaluation scores
on commonly used reasoning datasets. In contrast with existing metrics, ROSCOE
can measure semantic consistency, logicality, informativeness, fluency, and
factuality - among other traits - by leveraging properties of step-by-step
rationales. We empirically verify the strength of our metrics on five human
annotated and six programmatically perturbed diagnostics datasets - covering a
diverse set of tasks that require reasoning skills and show that ROSCOE can
consistently outperform baseline metrics.