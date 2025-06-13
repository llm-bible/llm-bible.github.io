---
layout: publication
title: 'Promptwise: Online Learning For Cost-aware Prompt Assignment In Generative Models'
authors: Xiaoyan Hu, Lauren Pick, Ho-fung Leung, Farzan Farnia
conference: "Arxiv"
year: 2025
bibkey: hu2025online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18901"}
tags: ['Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Prompting']
---
The rapid advancement of generative AI models has provided users with numerous options to address their prompts. When selecting a generative AI model for a given prompt, users should consider not only the performance of the chosen model but also its associated service cost. The principle guiding such consideration is to select the least expensive model among the available satisfactory options. However, existing model-selection approaches typically prioritize performance, overlooking pricing differences between models. In this paper, we introduce PromptWise, an online learning framework designed to assign a sequence of prompts to a group of large language models (LLMs) in a cost-effective manner. PromptWise strategically queries cheaper models first, progressing to more expensive options only if the lower-cost models fail to adequately address a given prompt. Through numerical experiments, we demonstrate PromptWise's effectiveness across various tasks, including puzzles of varying complexity and code generation/translation tasks. The results highlight that PromptWise consistently outperforms cost-unaware baseline methods, emphasizing that directly assigning prompts to the most expensive models can lead to higher costs and potentially lower average performance.
