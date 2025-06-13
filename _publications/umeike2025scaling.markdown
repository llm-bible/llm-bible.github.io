---
layout: publication
title: 'Scaling Large Vision-language Models For Enhanced Multimodal Comprehension In Biomedical Image Analysis'
authors: Robinson Umeike, Neil Getty, Fangfang Xia, Rick Stevens
conference: "Arxiv"
year: 2025
bibkey: umeike2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.15370'}
tags: ['Efficiency and Optimization', 'Distillation', 'Applications', 'Multimodal Models', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated immense capabilities in understanding textual data and are increasingly being adopted to help researchers accelerate scientific discovery through knowledge extraction (information retrieval), knowledge distillation (summarizing key findings and methodologies into concise forms), and knowledge synthesis (aggregating information from multiple scientific sources to address complex queries, generate hypothesis and formulate experimental plans). However, scientific data often exists in both visual and textual modalities. Vision language models (VLMs) address this by incorporating a pretrained vision backbone for processing images and a cross-modal projector that adapts image tokens into the LLM dimensional space, thereby providing richer multimodal comprehension. Nevertheless, off-the-shelf VLMs show limited capabilities in handling domain-specific data and are prone to hallucinations. We developed intelligent assistants finetuned from LLaVA models to enhance multimodal understanding in low-dose radiation therapy (LDRT)-a benign approach used in the treatment of cancer-related illnesses. Using multilingual data from 42,673 articles, we devise complex reasoning and detailed description tasks for visual question answering (VQA) benchmarks. Our assistants, trained on 50,882 image-text pairs, demonstrate superior performance over base models as evaluated using LLM-as-a-judge approach, particularly in reducing hallucination and improving domain-specific comprehension.
