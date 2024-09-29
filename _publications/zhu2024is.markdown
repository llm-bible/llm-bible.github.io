---
layout: publication
title: "Is Larger Always Better? Evaluating And Prompting Large Language Models For Non-generative Medical Tasks"
authors: Zhu Yinghao, Gao Junyi, Wang Zixiang, Liao Weibin, Zheng Xiaochen, Liang Lifang, Wang Yasha, Pan Chengwei, Harrison Ewen M., Ma Liantao
conference: "Arxiv"
year: 2024
bibkey: zhu2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18525"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
The use of Large Language Models (LLMs) in medicine is growing but their ability to handle both structured Electronic Health Record (EHR) data and unstructured clinical notes is not well-studied. This study benchmarks various models including GPT-based LLMs BERT-based models and traditional clinical predictive models for non-generative medical tasks utilizing renowned datasets. We assessed 14 language models (9 GPT-based and 5 BERT-based) and 7 traditional predictive models using the MIMIC dataset (ICU patient records) and the TJH dataset (early COVID-19 EHR data) focusing on tasks such as mortality and readmission prediction disease hierarchy reconstruction and biomedical sentence matching comparing both zero-shot and finetuned performance. Results indicated that LLMs exhibited robust zero-shot predictive capabilities on structured EHR data when using well-designed prompting strategies frequently surpassing traditional models. However for unstructured medical texts LLMs did not outperform finetuned BERT models which excelled in both supervised and unsupervised tasks. Consequently while LLMs are effective for zero-shot learning on structured data finetuned BERT models are more suitable for unstructured texts underscoring the importance of selecting models based on specific task requirements and data characteristics to optimize the application of NLP technology in healthcare.
