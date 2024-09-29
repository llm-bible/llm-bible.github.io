---
layout: publication
title: DebateQA Evaluating Question Answering on Debatable Knowledge
authors: Xu Rongwu, Qi Xuan, Qi Zehan, Xu Wei, Guo Zhijiang
conference: "Arxiv"
year: 2024
bibkey: xu2024debateqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01419"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
The rise of large language models (LLMs) has enabled us to seek answers to inherently debatable questions on LLM chatbots necessitating a reliable way to evaluate their ability. However traditional QA benchmarks assume fixed answers are inadequate for this purpose. To address this we introduce DebateQA a dataset of 2941 debatable questions each accompanied by multiple human-annotated partial answers that capture a variety of perspectives. We develop two metrics Perspective Diversity which evaluates the comprehensiveness of perspectives and Dispute Awareness which assesses if the LLM acknowledges the questions debatable nature. Experiments demonstrate that both metrics align with human preferences and are stable across different underlying models. Using DebateQA with two metrics we assess 12 popular LLMs and retrieval-augmented generation methods. Our findings reveal that while LLMs generally excel at recognizing debatable issues their ability to provide comprehensive answers encompassing diverse perspectives varies considerably.
