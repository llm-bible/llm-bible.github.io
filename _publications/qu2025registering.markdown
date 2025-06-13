---
layout: publication
title: 'Registering Source Tokens To Target Language Spaces In Multilingual Neural Machine Translation'
authors: Zhi Qu, Yiran Wang, Jiannan Mao, Chenchen Ding, Hideki Tanaka, Masao Utiyama, Taro Watanabe
conference: "Arxiv"
year: 2025
bibkey: qu2025registering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02979"}
  - {name: "Code", url: "https://github.com/zhiqu22/mitre"}
tags: ['Fine-Tuning', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
The multilingual neural machine translation (MNMT) aims for arbitrary translations across multiple languages. Although MNMT-specific models trained on parallel data offer low costs in training and deployment, their performance consistently lags behind that of large language models (LLMs). In this work, we introduce registering, a novel method that enables a small MNMT-specific model to compete with LLMs. Specifically, we insert a set of artificial tokens specifying the target language, called registers, into the input sequence between the source and target tokens. By modifying the attention mask, the target token generation only pays attention to the activation of registers, representing the source tokens in the target language space. Experiments on EC-40, a large-scale benchmark, show that our method advances the state-of-the-art of MNMT. We further pre-train two models, namely MITRE (multilingual translation with registers), by 9.3 billion sentence pairs across 24 languages collected from public corpora. One of them, MITRE-913M, outperforms NLLB-3.3B, achieves comparable performance with commercial LLMs, and shows strong adaptability in fine-tuning. Finally, we open-source our models to facilitate further research and development in MNMT: https://github.com/zhiqu22/mitre.
