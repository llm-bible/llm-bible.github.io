---
layout: publication
title: Beyond Self-learned Attention Mitigating Attention Bias in Transformer-based Models Using Attention Guidance
authors: Gesi Jiri, Ahmed Iftekhar
conference: "Arxiv"
year: 2024
bibkey: gesi2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16790"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Transformer-based models have demonstrated considerable potential for source code modeling tasks in software engineering. However they are limited by their dependence solely on automatic self-attention weight learning mechanisms. Previous studies have shown that these models overemphasize delimiters added by tokenizers (e.g. CLS SEP) which may lead to overlooking essential information in the original input source code. To address this challenge we introduce SyntaGuid a novel approach that utilizes the observation that attention weights tend to be biased towards specific source code syntax tokens and abstract syntax tree (AST) elements in fine-tuned language models when they make correct predictions. SyntaGuid facilitates the guidance of attention-weight learning leading to improved model performance on various software engineering tasks. We evaluate the effectiveness of SyntaGuid on multiple tasks and demonstrate that it outperforms existing state-of-the-art models in overall performance without requiring additional data. Experimental result shows that SyntaGuid can improve overall performance up to 3.25 and fix up to 28.3 wrong predictions. Our work represents the first attempt to guide the attention of Transformer-based models towards critical source code tokens during fine-tuning highlighting the potential for enhancing Transformer-based models in software engineering.
