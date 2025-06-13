---
layout: publication
title: 'Enhancing Llms'' Reasoning-intensive Multimedia Search Capabilities Through Fine-tuning And Reinforcement Learning'
authors: Jinzheng Li, Sibo Ju, Yanzhou Su, Hongguang Li, Yiqing Shen
conference: "Arxiv"
year: 2025
bibkey: li2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18831"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Existing large language models (LLMs) driven search agents typically rely on prompt engineering to decouple the user queries into search plans, limiting their effectiveness in complex scenarios requiring reasoning. Furthermore, they suffer from excessive token consumption due to Python-based search plan representations and inadequate integration of multimedia elements for both input processing and response generation. To address these challenges, we introduce SearchExpert, a training method for LLMs to improve their multimedia search capabilities in response to complex search queries. Firstly, we reformulate the search plan in an efficient natural language representation to reduce token consumption. Then, we propose the supervised fine-tuning for searching (SFTS) to fine-tune LLM to adapt to these representations, together with an automated dataset construction pipeline. Secondly, to improve reasoning-intensive search capabilities, we propose the reinforcement learning from search feedback (RLSF) that takes the search results planned by LLM as the reward signals. Thirdly, we propose a multimedia understanding and generation agent that enables the fine-tuned LLM to process visual input and produce visual output during inference. Finally, we establish an automated benchmark construction pipeline and a human evaluation framework. Our resulting benchmark, SearchExpertBench-25, comprises 200 multiple-choice questions spanning financial and international news scenarios that require reasoning in searching. Experiments demonstrate that SearchExpert outperforms the commercial LLM search method (Perplexity Pro) by 36.60% on the existing FinSearchBench-24 benchmark and 54.54% on our proposed SearchExpertBench-25. Human evaluations further confirm the superior readability.
