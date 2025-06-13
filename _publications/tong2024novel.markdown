---
layout: publication
title: 'T3: A Novel Zero-shot Transfer Learning Framework Iteratively Training On An Assistant Task For A Target Task'
authors: Xindi Tong, Yujin Zhu, Shijian Fan, Liang Xu
conference: "Arxiv"
year: 2024
bibkey: tong2024novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17640"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Long text summarization, gradually being essential for efficiently processing
large volumes of information, stays challenging for Large Language Models
(LLMs) such as GPT and LLaMA families because of the insufficient open-sourced
training datasets and the high requirement of contextual details dealing. To
address the issue, we design a novel zero-shot transfer learning framework,
abbreviated as T3, to iteratively training a baseline LLM on an assistant task
for the target task, where the former should own richer data resources and
share structural or semantic similarity with the latter. In practice, T3 is
approached to deal with the long text summarization task by utilizing question
answering as the assistant task, and further validated its effectiveness on the
BBC summary, NarraSum, FairytaleQA, and NLQuAD datasets, with up to nearly 14%
improvement in ROUGE, 35% improvement in BLEU, and 16% improvement in Factscore
compared to three baseline LLMs, demonstrating its potential for more
assistant-target task combinations.
