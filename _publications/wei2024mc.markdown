---
layout: publication
title: 'Mc-cot: A Modular Collaborative Cot Framework For Zero-shot Medical-vqa With LLM And MLLM Integration'
authors: Lai Wei, Wenkai Wang, Xiaoyu Shen, Yu Xie, Zhihao Fan, Xiaojin Zhang, Zhongyu Wei, Wei Chen
conference: "Arxiv"
year: 2024
bibkey: wei2024mc
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04521'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
In recent advancements, multimodal large language models (MLLMs) have been
fine-tuned on specific medical image datasets to address medical visual
question answering (Med-VQA) tasks. However, this common approach of
task-specific fine-tuning is costly and necessitates separate models for each
downstream task, limiting the exploration of zero-shot capabilities. In this
paper, we introduce MC-CoT, a modular cross-modal collaboration
Chain-of-Thought (CoT) framework designed to enhance the zero-shot performance
of MLLMs in Med-VQA by leveraging large language models (LLMs). MC-CoT improves
reasoning and information extraction by integrating medical knowledge and
task-specific guidance, where LLM provides various complex medical reasoning
chains and MLLM provides various observations of medical images based on
instructions of the LLM. Our experiments on datasets such as SLAKE, VQA-RAD,
and PATH-VQA show that MC-CoT surpasses standalone MLLMs and various
multimodality CoT frameworks in recall rate and accuracy. These findings
highlight the importance of incorporating background information and detailed
guidance in addressing complex zero-shot Med-VQA tasks.
