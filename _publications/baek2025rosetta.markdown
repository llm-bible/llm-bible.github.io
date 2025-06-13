---
layout: publication
title: 'Rosetta-pl: Propositional Logic As A Benchmark For Large Language Model Reasoning'
authors: Shaun Baek, Shaun Esua-mensah, Cyrus Tsui, Sejan Vigneswaralingam, Abdullah Alali, Michael Lu, Vasu Sharma, Sean O'brien, Kevin Zhu
conference: "Arxiv"
year: 2025
bibkey: baek2025rosetta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00001"}
tags: ['Applications', 'Training Techniques', 'GPT', 'Model Architecture']
---
Large Language Models (LLMs) are primarily trained on high-resource natural
languages, limiting their effectiveness in low-resource settings and in tasks
requiring deep logical reasoning. This research introduces Rosetta-PL, a
benchmark designed to evaluate LLMs' logical reasoning and generalization
capabilities in a controlled environment. We construct Rosetta-PL by
translating a dataset of logical propositions from Lean into a custom logical
language, which is then used to fine-tune an LLM (e.g., GPT-4o). Our
experiments analyze the impact of the size of the dataset and the translation
methodology on the performance of the model. Our results indicate that
preserving logical relationships in the translation process significantly
boosts precision, with accuracy plateauing beyond roughly 20,000 training
samples. These insights provide valuable guidelines for optimizing LLM training
in formal reasoning tasks and improving performance in various low-resource
language applications.
