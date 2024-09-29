---
layout: publication
title: Laffi Leveraging Hybrid Natural Language Feedback For Fine45;tuning Language Models
authors: Li Qianxi, Cao Yingyue, Kang Jikun, Yang Tianpei, Chen Xi, Jin Jun, Taylor Matthew E.
conference: "Arxiv"
year: 2023
bibkey: li2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00907"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG']
---
Fine45;tuning Large Language Models (LLMs) adapts a trained model to specific downstream tasks significantly improving task45;specific performance. Supervised Fine45;Tuning (SFT) is a common approach where an LLM is trained to produce desired answers. However LLMs trained with SFT sometimes make simple mistakes and result in hallucinations on reasoning tasks such as question45;answering. Without external feedback it is difficult for SFT to learn a good mapping between the question and the desired answer especially with a small dataset. This paper introduces an alternative to SFT called Natural Language Feedback for Finetuning LLMs (LaFFi). LaFFi has LLMs directly predict the feedback they will receive from an annotator. We find that requiring such reflection can significantly improve the accuracy in in45;domain question45;answering tasks providing a promising direction for the application of natural language feedback in the realm of SFT LLMs. Additional ablation studies show that the portion of human45;annotated data in the annotated datasets affects the fine45;tuning performance.
