---
layout: publication
title: 'Flawn-t5: An Empirical Examination Of Effective Instruction-tuning Data Mixtures For Legal Reasoning'
authors: Niklaus Joel, Zheng Lucia, Mccarthy Arya D., Hahn Christopher, Rosen Brian M., Henderson Peter, Ho Daniel E., Honke Garrett, Liang Percy, Manning Christopher
conference: "Arxiv"
year: 2024
bibkey: niklaus2024flawn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02127"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Instruction tuning is an important step in making language models useful for
direct user interaction. However, many legal tasks remain out of reach for most
open LLMs and there do not yet exist any large scale instruction datasets for
the domain. This critically limits research in this application area. In this
work, we curate LawInstruct, a large legal instruction dataset, covering 17
jurisdictions, 24 languages and a total of 12M examples. We present evidence
that domain-specific pretraining and instruction tuning improve performance on
LegalBench, including improving Flan-T5 XL by 8 points or 16% over the
baseline. However, the effect does not generalize across all tasks, training
regimes, model sizes, and other factors. LawInstruct is a resource for
accelerating the development of models with stronger information processing and
decision making capabilities in the legal domain.
