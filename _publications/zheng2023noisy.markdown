---
layout: publication
title: 'Noisy Exemplars Make Large Language Models More Robust: A Domain-agnostic Behavioral Analysis'
authors: Hongyi Zheng, Abulhair Saparov
conference: "Arxiv"
year: 2023
bibkey: zheng2023noisy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00258"}
tags: ['Prompting', 'Security', 'Few-Shot', 'In-Context Learning']
---
Recent advances in prompt engineering enable large language models (LLMs) to
solve multi-hop logical reasoning problems with impressive accuracy. However,
there is little existing work investigating the robustness of LLMs with
few-shot prompting techniques. Therefore, we introduce a systematic approach to
test the robustness of LLMs in multi-hop reasoning tasks via domain-agnostic
perturbations. We include perturbations at multiple levels of abstractions
(e.g. lexical perturbations such as typos, and semantic perturbations such as
the inclusion of intermediate reasoning steps in the questions) to conduct
behavioral analysis on the LLMs. Throughout our experiments, we find that
models are more sensitive to certain perturbations such as replacing words with
their synonyms. We also demonstrate that increasing the proportion of perturbed
exemplars in the prompts improves the robustness of few-shot prompting methods.
