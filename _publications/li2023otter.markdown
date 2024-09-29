---
layout: publication
title: Otter A Multi-Modal Model with In-Context Instruction Tuning
authors: Li Bo, Zhang Yuanhan, Chen Liangyu, Wang Jinghao, Yang Jingkang, Liu Ziwei
conference: "Arxiv"
year: 2023
bibkey: li2023otter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03726"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) have demonstrated significant universal capabilities as few/zero-shot learners in various tasks due to their pre-training on vast amounts of text data as exemplified by GPT-3 which boosted to InstrctGPT and ChatGPT effectively following natural language instructions to accomplish real-world tasks. In this paper we propose to introduce instruction tuning into multi-modal models motivated by the Flamingo models upstream interleaved format pretraining dataset. We adopt a similar approach to construct our MultI-Modal In-Context Instruction Tuning (MIMIC-IT) dataset. We then introduce Otter a multi-modal model based on OpenFlamingo (open-sourced version of DeepMinds Flamingo) trained on MIMIC-IT and showcasing improved instruction-following ability and in-context learning. We also optimize OpenFlamingos implementation for researchers democratizing the required training resources from 1times A100 GPU to 4times RTX-3090 GPUs and integrate both OpenFlamingo and Otter into Huggingface Transformers for more researchers to incorporate the models into their customized training and inference pipelines.
