---
layout: publication
title: 'Automatic Pair Construction For Contrastive Post-training'
authors: Canwen Xu, Corby Rosset, Ethan C. Chau, Luciano Del Corro, Shweti Mahajan, Julian Mcauley, Jennifer Neville, Ahmed Hassan Awadallah, Nikhil Rao
conference: "Arxiv"
year: 2023
bibkey: xu2023automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.02263'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning']
---
Alignment serves as an important step to steer large language models (LLMs)
towards human preferences. In this paper, we propose an automatic way to
construct contrastive data for LLM, using preference pairs from multiple models
of varying strengths (e.g., InstructGPT, ChatGPT and GPT-4). We compare the
contrastive techniques of SLiC and DPO to SFT baselines and find that DPO
provides a step-function improvement even after continuing SFT saturates. We
also explore a data curriculum learning scheme for contrastive post-training,
which starts by learning from "easier" pairs and transitioning to "harder"
ones, which further improves alignment. Finally, we scale up our experiments to
train with more data and larger models like Orca. Remarkably, our automatic
contrastive post-training further improves the performance of Orca, already a
state-of-the-art instruction learning model tuned with GPT-4 outputs, to
outperform ChatGPT.
