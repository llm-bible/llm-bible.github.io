---
layout: publication
title: 'Improving Expert Radiology Report Summarization By Prompting Large Language Models With A Layperson Summary'
authors: Xingmeng Zhao, Tongnian Wang, Anthony Rios
conference: "Arxiv"
year: 2024
bibkey: zhao2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14500"}
tags: ['Applications', 'Reinforcement Learning', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Radiology report summarization (RRS) is crucial for patient care, requiring
concise "Impressions" from detailed "Findings." This paper introduces a novel
prompting strategy to enhance RRS by first generating a layperson summary. This
approach normalizes key observations and simplifies complex information using
non-expert communication techniques inspired by doctor-patient interactions.
Combined with few-shot in-context learning, this method improves the model's
ability to link general terms to specific findings. We evaluate this approach
on the MIMIC-CXR, CheXpert, and MIMIC-III datasets, benchmarking it against
7B/8B parameter state-of-the-art open-source large language models (LLMs) like
Meta-Llama-3-8B-Instruct. Our results demonstrate improvements in summarization
accuracy and accessibility, particularly in out-of-domain tests, with
improvements as high as 5% for some metrics.
