---
layout: publication
title: "Automatic Prompt Augmentation And Selection With Chain-of-thought From Labeled Data"
authors: Shum Kashun, Diao Shizhe, Zhang Tong
conference: "Arxiv"
year: 2023
bibkey: shum2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.12822"}
  - {name: "Code", url: "https://github.com/SHUMKASHUN/Automate-CoT"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Pruning', 'Reinforcement Learning']
---
Chain-of-thought (CoT) advances the reasoning abilities of large language models (LLMs) and achieves superior performance in complex reasoning tasks. However most CoT studies rely on carefully designed human-annotated rational chains to prompt LLMs posing challenges for real-world applications where labeled data is available without rational chains. This paper proposes a new strategy Automate-CoT (Automatic Prompt Augmentation and Selection with Chain-of-Thought) that can bypass human engineering of CoT by automatically augmenting rational chains from a small labeled dataset and then pruning low-quality chains to construct a candidate pool of machine-generated rationale chains based on the labels. Finally it selects the optimal combination of several rationale chains from the pool for CoT prompting by employing a variance-reduced policy gradient strategy to estimate the significance of each example. Automate-CoT enables a quick adaptation of the CoT technique to different tasks. Experimental results demonstrate the effectiveness of our method where competitive results are achieved on arithmetic reasoning (+2.737;) commonsense reasoning (+3.437;) symbolic reasoning (+3.237;) and non-reasoning tasks (+2.537;). The code is available at https://github.com/SHUMKASHUN/Automate-CoT."
