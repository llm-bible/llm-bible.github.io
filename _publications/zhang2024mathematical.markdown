---
layout: publication
title: 'MAVIS: Mathematical Visual Instruction Tuning With An Automatic Data Engine'
authors: Renrui Zhang, Xinyu Wei, Dongzhi Jiang, Ziyu Guo, Shicheng Li, Yichi Zhang, Chengzhuo Tong, Jiaming Liu, Aojun Zhou, Bin Wei, Shanghang Zhang, Peng Gao, Chunyuan Li, Hongsheng Li
conference: "Arxiv"
year: 2024
bibkey: zhang2024mathematical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08739"}
  - {name: "Code", url: "https://github.com/ZrrSkywalker/MAVIS"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Has Code']
---
The mathematical capabilities of Multi-modal Large Language Models (MLLMs)
remain under-explored with three areas to be improved: visual encoding of math
diagrams, diagram-language alignment, and chain-of-thought (CoT) reasoning.
This draws forth an urgent demand for an effective training paradigm and a
large-scale, comprehensive dataset with detailed CoT rationales, which is
challenging to collect and costly to annotate manually. To tackle this issue,
we propose MAVIS, a MAthematical VISual instruction tuning pipeline for MLLMs,
featuring an automatic data engine to efficiently create mathematical visual
datasets. We design the data generation process to be entirely independent of
human intervention or GPT API usage, while ensuring the diagram-caption
correspondence, question-answer correctness, and CoT reasoning quality. With
this approach, we curate two datasets, MAVIS-Caption (558K diagram-caption
pairs) and MAVIS-Instruct (834K visual math problems with CoT rationales), and
propose four progressive stages for training MLLMs from scratch. First, we
utilize MAVIS-Caption to fine-tune a math-specific vision encoder (CLIP-Math)
through contrastive learning, tailored for improved diagram visual encoding.
Second, we also leverage MAVIS-Caption to align the CLIP-Math with a large
language model (LLM) by a projection layer, enhancing vision-language alignment
in mathematical domains. Third, we adopt MAVIS-Instruct to perform the
instruction tuning for robust problem-solving skills, and term the resulting
model as MAVIS-7B. Fourth, we apply Direct Preference Optimization (DPO) to
enhance the CoT capabilities of our model, further refining its step-wise
reasoning performance. Code and data will be released at
https://github.com/ZrrSkywalker/MAVIS
