---
layout: publication
title: 'A Course Correction In Steerability Evaluation: Revealing Miscalibration And Side Effects In Llms'
authors: Trenton Chang, Tobias Schnabel, Adith Swaminathan, Jenna Wiens
conference: "Arxiv"
year: 2025
bibkey: chang2025course
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23816"}
  - {name: "Code", url: "https://github.com/MLD3/steerability"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Despite advances in large language models (LLMs) on reasoning and instruction-following benchmarks, it remains unclear whether they can reliably produce outputs aligned with a broad variety of user goals, a concept we refer to as steerability. The abundance of methods proposed to modify LLM behavior makes it unclear whether current LLMs are already steerable, or require further intervention. In particular, LLMs may exhibit (i) poor coverage, where rare user goals are underrepresented; (ii) miscalibration, where models overshoot requests; and (iii) side effects, where changes to one dimension of text inadvertently affect others. To systematically evaluate these failures, we introduce a framework based on a multi-dimensional goal space that models user goals and LLM outputs as vectors with dimensions corresponding to text attributes (e.g., reading difficulty). Applied to a text-rewriting task, we find that current LLMs struggle with steerability, as side effects are persistent. Interventions to improve steerability, such as prompt engineering, best-of-\\(N\\) sampling, and reinforcement learning fine-tuning, have varying effectiveness, yet side effects remain problematic. Our findings suggest that even strong LLMs struggle with steerability, and existing alignment strategies may be insufficient. We open-source our steerability evaluation framework at https://github.com/MLD3/steerability.
