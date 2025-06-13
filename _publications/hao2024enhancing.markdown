---
layout: publication
title: 'CITI: Enhancing Tool Utilizing Ability In Large Language Models Without Sacrificing General Performance'
authors: Yupu Hao, Pengfei Cao, Zhuoran Jin, Huanxuan Liao, Yubo Chen, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2024
bibkey: hao2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13202"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Tool learning enables the Large Language Models (LLMs) to interact with the
external environment by invoking tools, enriching the accuracy and capability
scope of LLMs. However, previous works predominantly focus on improving model's
tool-utilizing accuracy and the ability to generalize to new, unseen tools,
excessively forcing LLMs to adjust specific tool-invoking pattern without
considering the harm to model's general performance. This deviates from the
actual applications and original intention of integrating tools to enhance
model. To tackle this problem, we dissect the capability trade-offs by
examining the hidden representation changes and the gradient-based importance
score of model's components. Based on the analysis result, we propose a
Component Importance-based Tool-utilizing ability Injection method (CITI).
According to the gradient-based importance score of different components, it
alleviates the capability conflicts caused by fine-tuning process by applying
distinct training strategies to different components. CITI applies
Mixture-Of-LoRA (MOLoRA) for important components. Meanwhile, it fine-tunes the
parameters of few components deemed less important in the backbone of the LLM,
while keeping other parameters frozen. CITI can effectively enhance the model's
tool-utilizing capability without excessively compromising its general
performance. Experimental results demonstrate that our approach achieves
outstanding performance across a range of evaluation metrics.
