---
layout: publication
title: Source-aware Training Enables Knowledge Attribution In Language Models
authors: Khalifa Muhammad, Wadden David, Strubell Emma, Lee Honglak, Wang Lu, Beltagy Iz, Peng Hao
conference: "Arxiv"
year: 2024
bibkey: khalifa2024source
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01019"}
  - {name: "Code", url: "https://github.com/mukhal/intrinsic-source-citation\"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) learn a vast amount of knowledge during pretraining but they are often oblivious to the source(s) of such knowledge. We investigate the problem of intrinsic source citation where LLMs are required to cite the pretraining source supporting a generated response. Intrinsic source citation can enhance LLM transparency interpretability and verifiability. To give LLMs such ability we explore source-aware training -- a recipe that involves (i) training the LLM to associate unique source document identifiers with the knowledge in each document followed by (ii) an instruction-tuning stage to teach the LLM to cite a supporting pretraining source when prompted. Source-aware training borrows from existing pretraining/fine-tuning frameworks and requires minimal changes to the model architecture or implementation. Through experiments on synthetic data we demonstrate that our training recipe can enable faithful attribution to the pretraining data without a substantial impact on the models perplexity compared to standard pretraining. Our findings also highlight the importance of pretraining data augmentation in achieving attribution. Code and data available here (url)https://github.com/mukhal/intrinsic-source-citation\}
