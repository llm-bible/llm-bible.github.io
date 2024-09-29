---
layout: publication
title: Unimot Unified Molecule45;text Language Model With Discrete Token Representation
authors: Zhang Juzheng, Bian Yatao, Chen Yongqiang, Yao Quanming
conference: "Arxiv"
year: 2024
bibkey: zhang2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00863"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques']
---
The remarkable success of Large Language Models (LLMs) across diverse tasks has driven the research community to extend their capabilities to molecular applications. However most molecular LLMs employ adapter45;based architectures that do not treat molecule and text modalities equally and lack a supervision signal for the molecule modality. To address these issues we introduce UniMoT a Unified Molecule45;Text LLM adopting a tokenizer45;based architecture that expands the vocabulary of LLM with molecule tokens. Specifically we introduce a Vector Quantization45;driven tokenizer that incorporates a Q45;Former to bridge the modality gap between molecule and text. This tokenizer transforms molecules into sequences of molecule tokens with causal dependency encapsulating high45;level molecular and textual information. Equipped with this tokenizer UniMoT can unify molecule and text modalities under a shared token representation and an autoregressive training paradigm enabling it to interpret molecules as a foreign language and generate them as text. Following a four45;stage training scheme UniMoT emerges as a multi45;modal generalist capable of performing both molecule45;to45;text and text45;to45;molecule tasks. Extensive experiments demonstrate that UniMoT achieves state45;of45;the45;art performance across a wide range of molecule comprehension and generation tasks.
