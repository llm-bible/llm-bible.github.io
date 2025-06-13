---
layout: publication
title: 'Scaling Test-time Compute For Low-resource Languages: Multilingual Reasoning In Llms'
authors: Khanh-tung Tran, Barry O'sullivan, Hoang D. Nguyen
conference: "Arxiv"
year: 2025
bibkey: tran2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02890"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Ethics and Bias']
---
Recent advances in test-time compute scaling have enabled Large Language
Models (LLMs) to tackle deep reasoning tasks by generating a chain-of-thought
(CoT) that includes trial and error, backtracking, and intermediate reasoning
steps before producing the final answer. However, these techniques have been
applied predominantly to popular languages, such as English, leaving reasoning
in low-resource languages underexplored and misaligned. In this work, we
investigate the multilingual mechanism by which LLMs internally operate in a
latent space biased toward their inherently dominant language. To leverage this
phenomenon for low-resource languages, we train models to generate the CoT in
English while outputting the final response in the target language, given input
in the low-resource language. Our experiments demonstrate that this approach,
named English-Pivoted CoT Training, outperforms other baselines, including
training to generate both the CoT and the final response solely in the target
language, with up to 28.33% improvement. Further analysis provides novel
insights into the relationships between reasoning and multilinguality of LLMs,
prompting for better approaches in developing multilingual large reasoning
models
