---
layout: publication
title: 'Memory-augmented Multimodal Llms For Surgical VQA Via Self-contained Inquiry'
authors: Wenjun Hou, Yi Cheng, Kaishuai Xu, Yan Hu, Wenjie Li, Jiang Liu
conference: "Arxiv"
year: 2024
bibkey: hou2024memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10937'}
tags: ['RAG', 'Security', 'Tools', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Comprehensively understanding surgical scenes in Surgical Visual Question
Answering (Surgical VQA) requires reasoning over multiple objects. Previous
approaches address this task using cross-modal fusion strategies to enhance
reasoning ability. However, these methods often struggle with limited scene
understanding and question comprehension, and some rely on external resources
(e.g., pre-extracted object features), which can introduce errors and
generalize poorly across diverse surgical environments. To address these
challenges, we propose SCAN, a simple yet effective memory-augmented framework
that leverages Multimodal LLMs to improve surgical context comprehension via
Self-Contained Inquiry. SCAN operates autonomously, generating two types of
memory for context augmentation: Direct Memory (DM), which provides multiple
candidates (or hints) to the final answer, and Indirect Memory (IM), which
consists of self-contained question-hint pairs to capture broader scene
context. DM directly assists in answering the question, while IM enhances
understanding of the surgical scene beyond the immediate query. Reasoning over
these object-aware memories enables the model to accurately interpret images
and respond to questions. Extensive experiments on three publicly available
Surgical VQA datasets demonstrate that SCAN achieves state-of-the-art
performance, offering improved accuracy and robustness across various surgical
scenarios.
