---
layout: publication
title: 'Large Language Models Can Better Understand Knowledge Graphs Than We Thought'
authors: Xinbang Dai, Yuncheng Hua, Tongtong Wu, Yang Sheng, Qiu Ji, Guilin Qi
conference: "Arxiv"
year: 2024
bibkey: dai2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11541"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Prompting', 'Applications', 'Attention Mechanism']
---
When we integrate factual knowledge from knowledge graphs (KGs) into large
language models (LLMs) to enhance their performance, the cost of injection
through training increases with the scale of the models. Consequently, there is
significant interest in developing prompt strategies that effectively
incorporate KG information into LLMs. However, the community has not yet
comprehensively understood how LLMs process and interpret KG information in
different input formats and organizations within prompts, and researchers often
rely on trial and error. To address this gap, we design extensive experiments
to empirically study LLMs' comprehension of different KG prompts. At the
literal level, we reveal LLMs' preferences for various input formats (from
linearized triples to fluent natural language text). At the attention
distribution level, we discuss the underlying mechanisms driving these
preferences. We then investigate how the organization of structured knowledge
impacts LLMs and evaluate LLMs' robustness in processing and utilizing KG
information in practical scenarios. Our experiments show that (1) linearized
triples are more effective than fluent NL text in helping LLMs understand KG
information and answer fact-intensive questions; (2) Different LLMs exhibit
varying preferences for different organizational formats of triples; (3) LLMs
with larger scales are more susceptible to noisy, incomplete subgraphs.
