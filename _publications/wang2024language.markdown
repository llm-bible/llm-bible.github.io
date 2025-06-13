---
layout: publication
title: 'Language Models As Continuous Self-evolving Data Engineers'
authors: Peidong Wang, Ming Wang, Zhiming Ma, Xiaocui Yang, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song
conference: "Arxiv"
year: 2024
bibkey: wang2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15151"}
  - {name: "Code", url: "https://github.com/Control-derek/LANCE"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities on
various tasks, while the further evolvement is limited to the lack of
high-quality training data. In addition, traditional training approaches rely
too much on expert-labeled data, setting a ceiling on the performance of LLMs.
To address this issue, we propose a novel paradigm named LANCE (LANguage models
as Continuous self-Evolving data engineers) that enables LLMs to train
themselves by autonomously generating, cleaning, reviewing, and annotating data
with preference information. Our approach demonstrates that LLMs can serve as
continuous self-evolving data engineers, significantly reducing the time and
cost of the post-training data construction. Through iterative fine-tuning on
Qwen2 series models, we validate the effectiveness of LANCE across various
tasks, showing that it can maintain high-quality data generation and
continuously improve model performance. Across multiple benchmark dimensions,
LANCE results in an average score enhancement of 3.64 for Qwen2-7B and 1.75 for
Qwen2-7B-Instruct. This training paradigm with autonomous data construction not
only reduces the reliance on human experts or external models but also ensures
that the data aligns with human preferences, paving the way for the development
of future superintelligent systems that can exceed human capabilities. Codes
are available at: https://github.com/Control-derek/LANCE.
