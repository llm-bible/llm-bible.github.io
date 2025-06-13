---
layout: publication
title: 'Rvtbench: A Benchmark For Visual Reasoning Tasks'
authors: Yiqing Shen, Chenjia Li, Chenxiao Fan, Mathias Unberath
conference: "Arxiv"
year: 2025
bibkey: shen2025benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11838'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Visual reasoning, the capability to interpret visual input in response to implicit text query through multi-step reasoning, remains a challenge for deep learning models due to the lack of relevant benchmarks. Previous work in visual reasoning has primarily focused on reasoning segmentation, where models aim to segment objects based on implicit text queries. This paper introduces reasoning visual tasks (RVTs), a unified formulation that extends beyond traditional video reasoning segmentation to a diverse family of visual language reasoning problems, which can therefore accommodate multiple output formats including bounding boxes, natural language descriptions, and question-answer pairs. Correspondingly, we identify the limitations in current benchmark construction methods that rely solely on large language models (LLMs), which inadequately capture complex spatial-temporal relationships and multi-step reasoning chains in video due to their reliance on token representation, resulting in benchmarks with artificially limited reasoning complexity. To address this limitation, we propose a novel automated RVT benchmark construction pipeline that leverages digital twin (DT) representations as structured intermediaries between perception and the generation of implicit text queries. Based on this method, we construct RVTBench, a RVT benchmark containing 3,896 queries of over 1.2 million tokens across four types of RVT (segmentation, grounding, VQA and summary), three reasoning categories (semantic, spatial, and temporal), and four increasing difficulty levels, derived from 200 video sequences. Finally, we propose RVTagent, an agent framework for RVT that allows for zero-shot generalization across various types of RVT without task-specific fine-tuning.
