---
layout: publication
title: 'PAPILLON: Privacy Preservation From Internet-based And Local Language Model Ensembles'
authors: Li Siyan, Vethavikashini Chithrra Raghuram, Omar Khattab, Julia Hirschberg, Zhou Yu
conference: "Arxiv"
year: 2024
bibkey: siyan2024privacy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17127'}
  - {name: "Code", url: 'https://github.com/siyan-sylvia-li/PAPILLON'}
tags: ['Has Code', 'Efficiency and Optimization', 'Tools', 'Merging', 'Prompting']
---
Users can divulge sensitive information to proprietary LLM providers, raising
significant privacy concerns. While open-source models, hosted locally on the
user's machine, alleviate some concerns, models that users can host locally are
often less capable than proprietary frontier models. Toward preserving user
privacy while retaining the best quality, we propose Privacy-Conscious
Delegation, a novel task for chaining API-based and local models. We utilize
recent public collections of user-LLM interactions to construct a natural
benchmark called PUPA, which contains personally identifiable information
(PII). To study potential approaches, we devise PAPILLON, a multi-stage LLM
pipeline that uses prompt optimization to address a simpler version of our
task. Our best pipeline maintains high response quality for 85.5% of user
queries while restricting privacy leakage to only 7.5%. We still leave a large
margin to the generation quality of proprietary LLMs for future work. Our data
and code is available at https://github.com/siyan-sylvia-li/PAPILLON.
