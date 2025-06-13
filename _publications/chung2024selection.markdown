---
layout: publication
title: 'Selection-p: Self-supervised Task-agnostic Prompt Compression For Faithfulness And Transferability'
authors: Tsz Ting Chung, Leyang Cui, Lemao Liu, Xinting Huang, Shuming Shi, Dit-yan Yeung
conference: "Arxiv"
year: 2024
bibkey: chung2024selection
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.11786'}
tags: ['RAG', 'Training Techniques', 'Model Architecture', 'GPT', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in a
wide range of natural language processing tasks when leveraging in-context
learning. To mitigate the additional computational and financial costs
associated with in-context learning, several prompt compression methods have
been proposed to compress the in-context learning prompts. Despite their
success, these methods face challenges with transferability due to
model-specific compression, or rely on external training data, such as GPT-4.
In this paper, we investigate the ability of LLMs to develop a unified
compression method that discretizes uninformative tokens, utilizing a
self-supervised pre-training technique. By introducing a small number of
parameters during the continual pre-training, the proposed Selection-p produces
a probability for each input token, indicating whether to preserve or discard
it. Experiments show Selection-p achieves state-of-the-art performance across
numerous classification tasks, achieving compression rates of up to 10 times
while experiencing only a marginal 0.8% decrease in performance. Moreover, it
exhibits superior transferability to different models compared to prior work.
Additionally, we further analyze how Selection-p helps maintain performance on
in-context learning with long contexts.
