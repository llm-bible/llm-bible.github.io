---
layout: publication
title: 'Harmaug: Effective Data Augmentation For Knowledge Distillation Of Safety Guard Models'
authors: Seanie Lee, Haebin Seong, Dong Bok Lee, Minki Kang, Xiaoyin Chen, Dominik Wagner, Yoshua Bengio, Juho Lee, Sung Ju Hwang
conference: "Arxiv"
year: 2024
bibkey: lee2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01524"}
tags: ['Responsible AI', 'Security', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Distillation', 'Prompting', 'Applications']
---
Safety guard models that detect malicious queries aimed at large language
models (LLMs) are essential for ensuring the secure and responsible deployment
of LLMs in real-world applications. However, deploying existing safety guard
models with billions of parameters alongside LLMs on mobile devices is
impractical due to substantial memory requirements and latency. To reduce this
cost, we distill a large teacher safety guard model into a smaller one using a
labeled dataset of instruction-response pairs with binary harmfulness labels.
Due to the limited diversity of harmful instructions in the existing labeled
dataset, naively distilled models tend to underperform compared to larger
models. To bridge the gap between small and large models, we propose HarmAug, a
simple yet effective data augmentation method that involves jailbreaking an LLM
and prompting it to generate harmful instructions. Given a prompt such as,
"Make a single harmful instruction prompt that would elicit offensive content",
we add an affirmative prefix (e.g., "I have an idea for a prompt:") to the
LLM's response. This encourages the LLM to continue generating the rest of the
response, leading to sampling harmful instructions. Another LLM generates a
response to the harmful instruction, and the teacher model labels the
instruction-response pair. We empirically show that our HarmAug outperforms
other relevant baselines. Moreover, a 435-million-parameter safety guard model
trained with HarmAug achieves an F1 score comparable to larger models with over
7 billion parameters, and even outperforms them in AUPRC, while operating at
less than 25% of their computational cost.
