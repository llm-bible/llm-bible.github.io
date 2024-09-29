---
layout: publication
title: "Evaluating Generative Language Models In Information Extraction As Subjective Question Correction"
authors: Fan Yuchen, Liu Yantao, Yao Zijun, Yu Jifan, Hou Lei, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: fan2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03532"}
  - {name: "Code", url: "https://github.com/THU-KEG/SQC-Score"}
tags: ['Ethics And Bias', 'Has Code']
---
Modern Large Language Models (LLMs) have showcased remarkable prowess in various tasks necessitating sophisticated cognitive behaviors. Nevertheless a paradoxical performance discrepancy is observed where these models underperform in seemingly elementary tasks like relation extraction and event extraction due to two issues in conventional evaluation. (1) The imprecision of existing evaluation metrics that struggle to effectively gauge semantic consistency between model outputs and ground truth and (2) The inherent incompleteness of evaluation benchmarks primarily due to restrictive human annotation schemas resulting in underestimated LLM performances. Inspired by the principles in subjective question correction we propose a new evaluation method SQC-Score. This method innovatively utilizes LLMs fine-tuned through subjective question correction data to refine matching between model outputs and golden labels. Additionally by incorporating a Natural Language Inference (NLI) model SQC-Score enriches golden labels addressing benchmark incompleteness by acknowledging correct yet previously omitted answers. Results on three information extraction tasks show that SQC-Score is more preferred by human annotators than the baseline metrics. Utilizing SQC-Score we conduct a comprehensive evaluation of the state-of-the-art LLMs and provide insights for future research for information extraction. Dataset and associated codes can be accessed at https://github.com/THU-KEG/SQC-Score."
