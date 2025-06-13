---
layout: publication
title: 'TASTE: Text-aligned Speech Tokenization And Embedding For Spoken Language Modeling'
authors: Liang-hsuan Tseng, Yi-chang Chen, Kuan-yi Lee, Da-shan Shiu, Hung-yi Lee
conference: "Arxiv"
year: 2025
bibkey: tseng2025text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07053"}
  - {name: "Code", url: "https://mtkresearch.github.io/TASTE-SpokenLM.github.io"}
tags: ['Training Techniques', 'Model Architecture', 'Tokenization', 'Language Modeling', 'Has Code', 'Attention Mechanism']
---
Recent efforts target spoken language models (SLMs) that not only listen but also speak for more natural human-LLM interaction. Joint speech-text modeling is a promising direction to achieve this. However, the effectiveness of recent speech tokens for joint modeling remains underexplored. To address this, we introduce Text-Aligned Speech Tokenization and Embedding (TASTE), a method that directly addresses the modality gap by aligning speech token with the corresponding text transcription during the tokenization stage. We propose a method that can achieve this through a attention-based aggregation mechanism and with speech reconstruction as the training objective. We conduct extensive experiments and show that TASTE can preserve essential paralinguistic information while dramatically reducing the token sequence length. With TASTE, we perform straightforward joint spoken language modeling by using Low-Rank Adaptation on the pre-trained text LLM. Experimental results show that TASTE-based SLMs perform comparable to previous work on SALMON and StoryCloze; while significantly outperform other pre-trained SLMs on speech continuation across subjective and objective evaluations. To our knowledge, TASTE is the first end-to-end approach that utilizes a reconstruction objective to automatically learn a text-aligned speech tokenization and embedding suitable for spoken language modeling. Our demo, code, and model are available at https://mtkresearch.github.io/TASTE-SpokenLM.github.io.
