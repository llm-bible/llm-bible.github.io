---
layout: publication
title: 'Towards Leveraging Llms For Conditional QA'
authors: Hussain Syed-amad, Dakle Parag Pravin, Rallabandi Saikrishna, Raghavan Preethi
conference: "Arxiv"
year: 2023
bibkey: hussain2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01143"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
This study delves into the capabilities and limitations of Large Language Models (LLMs) in the challenging domain of conditional question-answering. Utilizing the Conditional Question Answering (CQA) dataset and focusing on generative models like T5 and UL2, we assess the performance of LLMs across diverse question types. Our findings reveal that fine-tuned LLMs can surpass the state-of-the-art (SOTA) performance in some cases, even without fully encoding all input context, with an increase of 7-8 points in Exact Match (EM) and F1 scores for Yes/No questions. However, these models encounter challenges in extractive question answering, where they lag behind the SOTA by over 10 points, and in mitigating the risk of injecting false information. A study with oracle-retrievers emphasizes the critical role of effective evidence retrieval, underscoring the necessity for advanced solutions in this area. Furthermore, we highlight the significant influence of evaluation metrics on performance assessments and advocate for a more comprehensive evaluation framework. The complexity of the task, the observed performance discrepancies, and the need for effective evidence retrieval underline the ongoing challenges in this field and underscore the need for future work focusing on refining training tasks and exploring prompt-based techniques to enhance LLM performance in conditional question-answering tasks.
