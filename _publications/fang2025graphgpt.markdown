---
layout: publication
title: 'GRAPHGPT-O: Synergistic Multimodal Comprehension And Generation On Graphs'
authors: Yi Fang, Bowen Jin, Jiacheng Shen, Sirui Ding, Qiaoyu Tan, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: fang2025graphgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11925"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
The rapid development of Multimodal Large Language Models (MLLMs) has enabled
the integration of multiple modalities, including texts and images, within the
large language model (LLM) framework. However, texts and images are usually
interconnected, forming a multimodal attributed graph (MMAG). It is
underexplored how MLLMs can incorporate the relational information
(\textit\{i.e.\}, graph structure) and semantic information (\textit\{i.e.,\} texts
and images) on such graphs for multimodal comprehension and generation. In this
paper, we propose GraphGPT-o, which supports omni-multimodal understanding and
creation on MMAGs. We first comprehensively study linearization variants to
transform semantic and structural information as input for MLLMs. Then, we
propose a hierarchical aligner that enables deep graph encoding, bridging the
gap between MMAGs and MLLMs. Finally, we explore the inference choices,
adapting MLLM to interleaved text and image generation in graph scenarios.
Extensive experiments on three datasets from different domains demonstrate the
effectiveness of our proposed method. Datasets and codes will be open-sourced
upon acceptance.
