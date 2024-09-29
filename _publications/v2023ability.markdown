---
layout: publication
title: In45;context Ability Transfer For Question Decomposition In Complex QA
authors: V Venktesh, Bhattacharya Sourangshu, Anand Avishek
conference: "Arxiv"
year: 2023
bibkey: v2023ability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18371"}
tags: ['Applications', 'Prompting', 'Training Techniques']
---
Answering complex questions is a challenging task that requires question decomposition and multistep reasoning for arriving at the solution. While existing supervised and unsupervised approaches are specialized to a certain task and involve training recently proposed prompt45;based approaches offer generalizable solutions to tackle a wide variety of complex question45;answering (QA) tasks. However existing prompt45;based approaches that are effective for complex QA tasks involve expensive hand annotations from experts in the form of rationales and are not generalizable to newer complex QA scenarios and tasks. We propose icat (In45;Context Ability Transfer) which induces reasoning capabilities in LLMs without any LLM fine45;tuning or manual annotation of in45;context samples. We transfer the ability to decompose complex questions to simpler questions or generate step45;by45;step rationales to LLMs by careful selection from available data sources of related tasks. We also propose an automated uncertainty45;aware exemplar selection approach for selecting examples from transfer data sources. Finally we conduct large45;scale experiments on a variety of complex QA tasks involving numerical reasoning compositional complex QA and heterogeneous complex QA which require decomposed reasoning. We show that ICAT convincingly outperforms existing prompt45;based solutions without involving any model training showcasing the benefits of re45;using existing abilities.
