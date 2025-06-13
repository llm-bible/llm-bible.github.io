---
layout: publication
title: 'In-context Ability Transfer For Question Decomposition In Complex QA'
authors: Venktesh V, Sourangshu Bhattacharya, Avishek Anand
conference: "Arxiv"
year: 2023
bibkey: v2023ability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18371"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
Answering complex questions is a challenging task that requires question
decomposition and multistep reasoning for arriving at the solution. While
existing supervised and unsupervised approaches are specialized to a certain
task and involve training, recently proposed prompt-based approaches offer
generalizable solutions to tackle a wide variety of complex question-answering
(QA) tasks. However, existing prompt-based approaches that are effective for
complex QA tasks involve expensive hand annotations from experts in the form of
rationales and are not generalizable to newer complex QA scenarios and tasks.
We propose, icat (In-Context Ability Transfer) which induces reasoning
capabilities in LLMs without any LLM fine-tuning or manual annotation of
in-context samples. We transfer the ability to decompose complex questions to
simpler questions or generate step-by-step rationales to LLMs, by careful
selection from available data sources of related tasks. We also propose an
automated uncertainty-aware exemplar selection approach for selecting examples
from transfer data sources. Finally, we conduct large-scale experiments on a
variety of complex QA tasks involving numerical reasoning, compositional
complex QA, and heterogeneous complex QA which require decomposed reasoning. We
show that ICAT convincingly outperforms existing prompt-based solutions without
involving any model training, showcasing the benefits of re-using existing
abilities.
