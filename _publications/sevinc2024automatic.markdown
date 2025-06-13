---
layout: publication
title: 'Autoreason: Automatic Few-shot Reasoning Decomposition'
authors: Arda Sevinc, Abdurrahman Gumus
conference: "Arxiv"
year: 2024
bibkey: sevinc2024automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06975'}
  - {name: "Code", url: 'https://github.com/miralab-ai/autoreason'}
tags: ['Has Code', 'Interpretability and Explainability', 'Few-Shot', 'Applications', 'Prompting']
---
Chain of Thought (CoT) was introduced in recent research as a method for
improving step-by-step reasoning in Large Language Models. However, CoT has
limited applications such as its need for hand-crafted few-shot exemplar
prompts and no capability to adjust itself to different queries.
  In this work, we propose a system to automatically generate rationales using
CoT. Our method improves multi-step implicit reasoning capabilities by
decomposing the implicit query into several explicit questions. This provides
interpretability for the model, improving reasoning in weaker LLMs. We test our
approach with two Q\&A datasets: StrategyQA and HotpotQA. We show an increase
in accuracy with both, especially on StrategyQA.
  To facilitate further research in this field, the complete source code for
this study has been made publicly available on GitHub:
https://github.com/miralab-ai/autoreason.
