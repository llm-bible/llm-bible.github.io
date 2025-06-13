---
layout: publication
title: 'Xiwu: A Basis Flexible And Learnable LLM For High Energy Physics'
authors: Zhengde Zhang, Yiyu Zhang, Haodong Yao, Jianwen Luo, Rui Zhao, Bo Huang, Jiameng Zhao, Yipu Liao, Ke Li, Lina Zhao, Jun Cao, Fazhi Qi, Changzheng Yuan
conference: "Arxiv"
year: 2024
bibkey: zhang2024basis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08001"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are undergoing a period of rapid updates and
changes, with state-of-the-art (SOTA) model frequently being replaced. When
applying LLMs to a specific scientific field, it's challenging to acquire
unique domain knowledge while keeping the model itself advanced. To address
this challenge, a sophisticated large language model system named as Xiwu has
been developed, allowing you switch between the most advanced foundation models
and quickly teach the model domain knowledge. In this work, we will report on
the best practices for applying LLMs in the field of high-energy physics (HEP),
including: a seed fission technology is proposed and some data collection and
cleaning tools are developed to quickly obtain domain AI-Ready dataset; a
just-in-time learning system is implemented based on the vector store
technology; an on-the-fly fine-tuning system has been developed to facilitate
rapid training under a specified foundation model. The results show that Xiwu
can smoothly switch between foundation models such as LLaMA, Vicuna, ChatGLM
and Grok-1. The trained Xiwu model is significantly outperformed the benchmark
model on the HEP knowledge question-and-answering and code generation. This
strategy significantly enhances the potential for growth of our model's
performance, with the hope of surpassing GPT-4 as it evolves with the
development of open-source models. This work provides a customized LLM for the
field of HEP, while also offering references for applying LLM to other fields,
the corresponding codes are available on Github.
