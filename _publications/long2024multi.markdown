---
layout: publication
title: 'Multi-expert Prompting Improves Reliability, Safety, And Usefulness Of Large Language Models'
authors: Do Xuan Long, Duong Ngoc Yen, Anh Tuan Luu, Kenji Kawaguchi, Min-yen Kan, Nancy F. Chen
conference: "Arxiv"
year: 2024
bibkey: long2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00492"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Model Architecture', 'Prompting']
---
We present Multi-expert Prompting, a novel enhancement of ExpertPrompting (Xu
et al., 2023), designed to improve the large language model (LLM) generation.
Specifically, it guides an LLM to fulfill an input instruction by simulating
multiple experts, aggregating their responses, and selecting the best among
individual and aggregated responses. This process is performed in a single
chain of thoughts through our seven carefully designed subtasks derived from
the Nominal Group Technique (Ven and Delbecq, 1974), a well-established
decision-making framework. Our evaluations demonstrate that Multi-expert
Prompting significantly outperforms ExpertPrompting and comparable baselines in
enhancing the truthfulness, factuality, informativeness, and usefulness of
responses while reducing toxicity and hurtfulness. It further achieves
state-of-the-art truthfulness by outperforming the best baseline by 8.69% with
ChatGPT. Multi-expert Prompting is efficient, explainable, and highly adaptable
to diverse scenarios, eliminating the need for manual prompt construction.
