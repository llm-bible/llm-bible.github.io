---
layout: publication
title: 'TAGS: A Test-time Generalist-specialist Framework With Retrieval-augmented Reasoning And Verification'
authors: Jianghao Wu, Feilong Tang, Yulong Li, Ming Hu, Haochen Xue, Shoaib Jameel, Yutong Xie, Imran Razzak
conference: "Arxiv"
year: 2025
bibkey: wu2025test
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18283'}
  - {name: "Code", url: 'https://github.com/JianghaoWu/TAGS'}
tags: ['Has Code', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances such as Chain-of-Thought prompting have significantly improved large language models (LLMs) in zero-shot medical reasoning. However, prompting-based methods often remain shallow and unstable, while fine-tuned medical LLMs suffer from poor generalization under distribution shifts and limited adaptability to unseen clinical scenarios. To address these limitations, we present TAGS, a test-time framework that combines a broadly capable generalist with a domain-specific specialist to offer complementary perspectives without any model fine-tuning or parameter updates. To support this generalist-specialist reasoning process, we introduce two auxiliary modules: a hierarchical retrieval mechanism that provides multi-scale exemplars by selecting examples based on both semantic and rationale-level similarity, and a reliability scorer that evaluates reasoning consistency to guide final answer aggregation. TAGS achieves strong performance across nine MedQA benchmarks, boosting GPT-4o accuracy by 13.8%, DeepSeek-R1 by 16.8%, and improving a vanilla 7B model from 14.1% to 23.9%. These results surpass several fine-tuned medical LLMs, without any parameter updates. The code will be available at https://github.com/JianghaoWu/TAGS.
