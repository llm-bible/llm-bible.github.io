---
layout: publication
title: Laffi\: Leveraging Hybrid Natural Language Feedback For Fine-tuning Language Models
authors: Li Qianxi, Cao Yingyue, Kang Jikun, Yang Tianpei, Chen Xi, Jin Jun, Taylor Matthew E.
conference: "Arxiv"
year: 2023
bibkey: li2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00907"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Fine-tuning Large Language Models (LLMs) adapts a trained model to specific downstream tasks significantly improving task-specific performance. Supervised Fine-Tuning (SFT) is a common approach where an LLM is trained to produce desired answers. However LLMs trained with SFT sometimes make simple mistakes and result in hallucinations on reasoning tasks such as question-answering. Without external feedback it is difficult for SFT to learn a good mapping between the question and the desired answer especially with a small dataset. This paper introduces an alternative to SFT called Natural Language Feedback for Finetuning LLMs (LaFFi). LaFFi has LLMs directly predict the feedback they will receive from an annotator. We find that requiring such reflection can significantly improve the accuracy in in-domain question-answering tasks providing a promising direction for the application of natural language feedback in the realm of SFT LLMs. Additional ablation studies show that the portion of human-annotated data in the annotated datasets affects the fine-tuning performance.
