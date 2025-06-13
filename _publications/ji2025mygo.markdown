---
layout: publication
title: 'Mygo Multiplex Cot: A Method For Self-reflection In Large Language Models Via Double Chain Of Thought Thinking'
authors: Shihao Ji, Zihui Song, Fucheng Zhong, Jisen Jia, Zhaobo Wu, Zheyi Cao, Tianhao Xu
conference: "Arxiv"
year: 2025
bibkey: ji2025mygo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13117"}
tags: ['Training Techniques', 'Model Architecture', 'Survey Paper', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Recent advancements in large language models (LLMs) have demonstrated their
impressive abilities in various reasoning and decision-making tasks. However,
the quality and coherence of the reasoning process can still benefit from
enhanced introspection and self-reflection. In this paper, we introduce
Multiplex CoT (Chain of Thought), a method that enables LLMs to simulate a form
of self-review while reasoning, by initiating double Chain of Thought (CoT)
thinking. Multiplex CoT leverages the power of iterative reasoning, where the
model generates an initial chain of thought and subsequently critiques and
refines this reasoning with a second round of thought generation. This
recursive approach allows for more coherent, logical, and robust answers,
improving the overall decision-making process. We demonstrate how this method
can be effectively implemented using simple prompt engineering in existing LLM
architectures, achieving an effect similar to that of the Learning-Refinement
Model (LRM) without the need for additional training. Additionally, we present
a practical guide for implementing the method in Google Colab, enabling easy
integration into real-world applications.
