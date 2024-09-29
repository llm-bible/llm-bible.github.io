---
layout: publication
title: 'Effectively Fine-tune To Improve Large Multimodal Models For Radiology Report Generation'
authors: Lu Yuzhe, Hong Sungmin, Shah Yash, Xu Panpan
conference: "Arxiv"
year: 2023
bibkey: lu2023effectively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01504"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Writing radiology reports from medical images requires a high level of domain expertise. It is time-consuming even for trained radiologists and can be error-prone for inexperienced radiologists. It would be appealing to automate this task by leveraging generative AI which has shown drastic progress in vision and language understanding. In particular Large Language Models (LLM) have demonstrated impressive capabilities recently and continued to set new state-of-the-art performance on almost all natural language tasks. While many have proposed architectures to combine vision models with LLMs for multimodal tasks few have explored practical fine-tuning strategies. In this work we proposed a simple yet effective two-stage fine-tuning protocol to align visual features to LLMs text embedding space as soft visual prompts. Our framework with OpenLLaMA-7B achieved state-of-the-art level performance without domain-specific pretraining. Moreover we provide detailed analyses of soft visual prompts and attention mechanisms shedding light on future research directions.
