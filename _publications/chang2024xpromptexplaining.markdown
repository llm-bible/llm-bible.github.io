---
layout: publication
title: Xpromptexplaining Large Language Modelx27;s Generation Via Joint Prompt Attribution
authors: Chang Yurui, Cao Bochuan, Wang Yujia, Chen Jinghui, Lin Lu
conference: "Arxiv"
year: 2024
bibkey: chang2024xpromptexplaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20404"}
tags: ['Applications', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Language Modeling', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have demonstrated impressive performances in complex text generation tasks. However the contribution of the input prompt to the generated content still remains obscure to humans underscoring the necessity of elucidating and explaining the causality between input and output pairs. Existing works for providing prompt-specific explanation often confine model output to be classification or next-word prediction. Few initial attempts aiming to explain the entire language generation often treat input prompt texts independently ignoring their combinatorial effects on the follow-up generation. In this study we introduce a counterfactual explanation framework based on joint prompt attribution XPrompt which aims to explain how a few prompt texts collaboratively influences the LLMs complete generation. Particularly we formulate the task of prompt attribution for generation interpretation as a combinatorial optimization problem and introduce a probabilistic algorithm to search for the casual input combination in the discrete space. We define and utilize multiple metrics to evaluate the produced explanations demonstrating both faithfulness and efficiency of our framework.
