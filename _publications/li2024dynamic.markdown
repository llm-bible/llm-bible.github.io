---
layout: publication
title: 'Dynamic Data Sampler For Cross-language Transfer Learning In Large Language Models'
authors: Yudong Li, Yuhao Feng, Wen Zhou, Zhe Zhao, Linlin Shen, Cheng Hou, Xianxu Hou
conference: "Arxiv"
year: 2024
bibkey: li2024dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.10626'}
tags: ['Attention Mechanism', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
Large Language Models (LLMs) have gained significant attention in the field
of natural language processing (NLP) due to their wide range of applications.
However, training LLMs for languages other than English poses significant
challenges, due to the difficulty in acquiring large-scale corpus and the
requisite computing resources. In this paper, we propose ChatFlow, a
cross-language transfer-based LLM, to address these challenges and train large
Chinese language models in a cost-effective manner. We employ a mix of Chinese,
English, and parallel corpus to continuously train the LLaMA2 model, aiming to
align cross-language representations and facilitate the knowledge transfer
specifically to the Chinese language model. In addition, we use a dynamic data
sampler to progressively transition the model from unsupervised pre-training to
supervised fine-tuning. Experimental results demonstrate that our approach
accelerates model convergence and achieves superior performance. We evaluate
ChatFlow on popular Chinese and English benchmarks, the results indicate that
it outperforms other Chinese models post-trained on LLaMA-2-7B.
