---
layout: publication
title: Vector45;quantized Input45;contextualized Soft Prompts For Natural Language Understanding
authors: Bhardwaj Rishabh, Saha Amrita, Hoi Steven C. H., Poria Soujanya
conference: "Arxiv"
year: 2022
bibkey: bhardwaj2022vector
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11024"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'Quantization', 'RAG', 'Reinforcement Learning', 'Tools']
---
Prompt Tuning has been largely successful as a parameter45;efficient method of conditioning large45;scale pre45;trained language models to perform downstream tasks. Thus far soft prompt tuning learns a fixed set of task45;specific continuous vectors i.e. soft tokens that remain static across the task samples. A fixed prompt however may not generalize well to the diverse kinds of inputs the task comprises. In order to address this we propose Vector45;quantized Input45;contextualized Prompts (VIP) as an extension to the soft prompt tuning framework. VIP particularly focuses on two aspects 45;45; contextual prompts that learns input45;specific contextualization of the soft prompt tokens through a small45;scale sentence encoder and quantized prompts that maps the contextualized prompts to a set of learnable codebook vectors through a Vector quantization network. On various language understanding tasks like SuperGLUE QA Relation classification NER and NLI VIP outperforms the soft prompt tuning (PT) baseline by an average margin of 1.1937;. Further our generalization studies show that VIP learns more robust prompt representations surpassing PT by a margin of 0.637; 45; 5.337; on Out45;of45;domain QA and NLI tasks respectively and by 0.7537; on Multi45;Task setup over 4 tasks spanning across 12 domains.
