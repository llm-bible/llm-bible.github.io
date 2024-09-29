---
layout: publication
title: Visual Prompting For Generalized Few-shot Segmentation\: A Multi-scale Approach
authors: Hossain Mir Rayat Imtiaz, Siam Mennatullah, Sigal Leonid, Little James J.
conference: "Arxiv"
year: 2024
bibkey: hossain2024visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11732"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Few Shot', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
The emergence of attention-based transformer models has led to their extensive use in various tasks due to their superior generalization and transfer properties. Recent research has demonstrated that such models when prompted appropriately are excellent for few-shot inference. However such techniques are under-explored for dense prediction tasks like semantic segmentation. In this work we examine the effectiveness of prompting a transformer-decoder with learned visual prompts for the generalized few-shot segmentation (GFSS) task. Our goal is to achieve strong performance not only on novel categories with limited examples but also to retain performance on base categories. We propose an approach to learn visual prompts with limited examples. These learned visual prompts are used to prompt a multiscale transformer decoder to facilitate accurate dense predictions. Additionally we introduce a unidirectional causal attention mechanism between the novel prompts learned with limited examples and the base prompts learned with abundant data. This mechanism enriches the novel prompts without deteriorating the base class performance. Overall this form of prompting helps us achieve state-of-the-art performance for GFSS on two different benchmark datasets COCO-20^i and Pascal-5^i without the need for test-time optimization (or transduction). Furthermore test-time optimization leveraging unlabelled test data can be used to improve the prompts which we refer to as transductive prompt tuning.
