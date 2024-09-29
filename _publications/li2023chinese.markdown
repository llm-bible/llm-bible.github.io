---
layout: publication
title: CFGPT\: Chinese Financial Assistant With Large Language Model
authors: Li Jiangtong, Bian Yuxuan, Wang Guoxuan, Lei Yang, Cheng Dawei, Ding Zhijun, Jiang Changjun
conference: "Arxiv"
year: 2023
bibkey: li2023chinese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10654"}
  - {name: "Code", url: "https://github.com/TongjiFinLab/CFGPT"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) have demonstrated great potential in natural language processing tasks within the financial domain. In this work we present a Chinese Financial Generative Pre-trained Transformer framework named CFGPT which includes a dataset~(CFData) for pre-training and supervised fine-tuning a financial LLM~(CFLLM) to adeptly manage financial texts and a deployment framework~(CFAPP) designed to navigate real-world financial applications. The CFData comprising both a pre-training dataset and a supervised fine-tuning dataset where the pre-training dataset collates Chinese financial data and analytics alongside a smaller subset of general-purpose text with 584M documents and 141B tokens in total and the supervised fine-tuning dataset is tailored for six distinct financial tasks embodying various facets of financial analysis and decision-making with 1.5M instruction pairs and 1.5B tokens in total. The CFLLM which is based on InternLM-7B to balance the model capability and size is trained on CFData in two stage continued pre-training and supervised fine-tuning. The CFAPP is centered on large language models (LLMs) and augmented with additional modules to ensure multifaceted functionality in real-world application. Our codes are released at https://github.com/TongjiFinLab/CFGPT."
