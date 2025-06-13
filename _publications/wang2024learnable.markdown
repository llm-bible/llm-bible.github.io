---
layout: publication
title: 'Learnable Item Tokenization For Generative Recommendation'
authors: Wenjie Wang, Honghui Bao, Xinyu Lin, Jizhi Zhang, Yongqi Li, Fuli Feng, See-kiong Ng, Tat-seng Chua
conference: "Arxiv"
year: 2024
bibkey: wang2024learnable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07314"}
tags: ['Tokenization', 'Model Architecture', 'Attention Mechanism', 'Ethics and Bias']
---
Utilizing powerful Large Language Models (LLMs) for generative recommendation
has attracted much attention. Nevertheless, a crucial challenge is transforming
recommendation data into the language space of LLMs through effective item
tokenization. Current approaches, such as ID, textual, and codebook-based
identifiers, exhibit shortcomings in encoding semantic information,
incorporating collaborative signals, or handling code assignment bias. To
address these limitations, we propose LETTER (a LEarnable Tokenizer for
generaTivE Recommendation), which integrates hierarchical semantics,
collaborative signals, and code assignment diversity to satisfy the essential
requirements of identifiers. LETTER incorporates Residual Quantized VAE for
semantic regularization, a contrastive alignment loss for collaborative
regularization, and a diversity loss to mitigate code assignment bias. We
instantiate LETTER on two models and propose a ranking-guided generation loss
to augment their ranking ability theoretically. Experiments on three datasets
validate the superiority of LETTER, advancing the state-of-the-art in the field
of LLM-based generative recommendation.
