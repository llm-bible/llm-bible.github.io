---
layout: publication
title: 'Enhancing Llm-based Text Classification In Political Science: Automatic Prompt Optimization And Dynamic Exemplar Selection For Few-shot Learning'
authors: Menglin Liu, Ge Shi
conference: "Arxiv"
year: 2024
bibkey: liu2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01466"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Ethics and Bias', 'Interpretability and Explainability', 'Interpretability', 'Training Techniques', 'Few-Shot', 'Prompting']
---
Large language models (LLMs) offer substantial promise for text
classification in political science, yet their effectiveness often depends on
high-quality prompts and exemplars. To address this, we introduce a three-stage
framework that enhances LLM performance through automatic prompt optimization,
dynamic exemplar selection, and a consensus mechanism. Our approach automates
prompt refinement using task-specific exemplars, eliminating speculative
trial-and-error adjustments and producing structured prompts aligned with
human-defined criteria. In the second stage, we dynamically select the most
relevant exemplars, ensuring contextually appropriate guidance for each query.
Finally, our consensus mechanism mimics the role of multiple human coders for a
single task, combining outputs from LLMs to achieve high reliability and
consistency at a reduced cost. Evaluated across tasks including sentiment
analysis, stance detection, and campaign ad tone classification, our method
enhances classification accuracy without requiring task-specific model
retraining or extensive manual adjustments to prompts. This framework not only
boosts accuracy, interpretability and transparency but also provides a
cost-effective, scalable solution tailored to political science applications.
An open-source Python package (PoliPrompt) is available on GitHub.
