---
layout: publication
title: 'Automatic Model Selection With Large Language Models For Reasoning'
authors: Zhao James Xu, Xie Yuxi, Kawaguchi Kenji, He Junxian, Xie Michael Qizhe
conference: "Arxiv"
year: 2023
bibkey: zhao2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14333"}
  - {name: "Code", url: "https://github.com/XuZhao0/Model-Selection-Reasoning"}
tags: ['GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Chain-of-Thought (CoT) and Program-Aided Language Models (PAL) represent two
distinct reasoning methods, each with its own strengths. CoT employs natural
language, offering flexibility and interpretability, while PAL utilizes
programming language, yielding more structured and rigorous logic. We introduce
a model selection method to combine the best of both worlds by employing a
large language model (LLM) to dynamically select between them. Our theoretical
analysis underscores the feasibility of this method, which is further
corroborated by empirical results. Our proposed method demonstrates significant
performance improvements across eight reasoning datasets with Codex, ChatGPT,
and GPT-4. Additionally, our method is complementary to self-consistency; when
integrated, it can further enhance performance while significantly reducing
computation costs. Moreover, we achieve new state-of-the-art results on GSM8K
and SVAMP, with respective accuracies of 96.8% and 93.7%. Our code, data and
prompts are available at https://github.com/XuZhao0/Model-Selection-Reasoning
