---
layout: publication
title: 'Intrinsic Evaluation Of Unlearning Using Parametric Knowledge Traces'
authors: Yihuai Hong, Lei Yu, Haiqin Yang, Shauli Ravfogel, Mor Geva
conference: "Arxiv"
year: 2024
bibkey: hong2024intrinsic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11614'}
  - {name: "Code", url: 'https://github.com/yihuaihong/ConceptVectors'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Security', 'Model Architecture', 'Reinforcement Learning']
---
The task of "unlearning" certain concepts in large language models (LLMs) has
attracted immense attention recently, due to its importance in mitigating
undesirable model behaviours, such as the generation of harmful, private, or
incorrect information. Current protocols to evaluate unlearning methods largely
rely on behavioral tests, without monitoring the presence of unlearned
knowledge within the model's parameters. This residual knowledge can be
adversarially exploited to recover the erased information post-unlearning. We
argue that unlearning should also be evaluated internally, by considering
changes in the parametric knowledge traces of the unlearned concepts. To this
end, we propose a general evaluation methodology that leverages vocabulary
projections to inspect concepts encoded in model parameters. We use this
approach to localize "concept vectors" - parameter vectors that encode concrete
concepts - and construct ConceptVectors, a benchmark dataset containing
hundreds of common concepts and their parametric knowledge traces within two
open-source LLMs. Evaluation on ConceptVectors shows that existing unlearning
methods minimally impact concept vectors and mostly suppress them during
inference, while directly ablating these vectors demonstrably removes the
associated knowledge and significantly reduces the model's susceptibility to
adversarial manipulation. Our results highlight limitations in behavioral-based
unlearning evaluations and call for future work to include parameter-based
evaluations. To support this, we release our code and benchmark at
https://github.com/yihuaihong/ConceptVectors.
