---
layout: publication
title: 'Token-level Adversarial Prompt Detection Based On Perplexity Measures And Contextual Information'
authors: Hu Zhengmian, Wu Gang, Mitra Saayan, Zhang Ruiyi, Sun Tong, Huang Heng, Swaminathan Viswanathan
conference: "Arxiv"
year: 2023
bibkey: hu2023token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11509"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
In recent years, Large Language Models (LLM) have emerged as pivotal tools in various applications. However, these models are susceptible to adversarial prompt attacks, where attackers can carefully curate input strings that mislead LLMs into generating incorrect or undesired outputs. Previous work has revealed that with relatively simple yet effective attacks based on discrete optimization, it is possible to generate adversarial prompts that bypass moderation and alignment of the models. This vulnerability to adversarial prompts underscores a significant concern regarding the robustness and reliability of LLMs. Our work aims to address this concern by introducing a novel approach to detecting adversarial prompts at a token level, leveraging the LLM's capability to predict the next token's probability. We measure the degree of the model's perplexity, where tokens predicted with high probability are considered normal, and those exhibiting high perplexity are flagged as adversarial. Additionaly, our method also integrates context understanding by incorporating neighboring token information to encourage the detection of contiguous adversarial prompt sequences. To this end, we design two algorithms for adversarial prompt detection: one based on optimization techniques and another on Probabilistic Graphical Models (PGM). Both methods are equipped with efficient solving methods, ensuring efficient adversarial prompt detection. Our token-level detection result can be visualized as heatmap overlays on the text sequence, allowing for a clearer and more intuitive representation of which part of the text may contain adversarial prompts.
