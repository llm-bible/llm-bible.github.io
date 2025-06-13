---
layout: publication
title: 'Everything Everywhere All At Once: Llms Can In-context Learn Multiple Tasks In Superposition'
authors: Zheyang Xiong, Ziyang Cai, John Cooper, Albert Ge, Vasilis Papageorgiou, Zack Sifakis, Angeliki Giannou, Ziqian Lin, Liu Yang, Saurabh Agarwal, Grigorios G Chrysos, Samet Oymak, Kangwook Lee, Dimitris Papailiopoulos
conference: "Arxiv"
year: 2024
bibkey: xiong2024everything
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05603'}
tags: ['Interpretability and Explainability', 'Transformer', 'Model Architecture', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable in-context learning
(ICL) capabilities. In this study, we explore a surprising phenomenon related
to ICL: LLMs can perform multiple, computationally distinct ICL tasks
simultaneously, during a single inference call, a capability we term "task
superposition". We provide empirical evidence of this phenomenon across various
LLM families and scales and show that this phenomenon emerges even if we train
the model to in-context learn one task at a time. We offer theoretical
explanations that this capability is well within the expressive power of
transformers. We also explore how LLMs internally compose task vectors during
superposition. Furthermore, we show that larger models can solve more ICL tasks
in parallel, and better calibrate their output distribution. Our findings offer
insights into the latent capabilities of LLMs, further substantiate the
perspective of "LLMs as superposition of simulators", and raise questions about
the mechanisms enabling simultaneous task execution.
