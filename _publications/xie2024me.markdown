---
layout: publication
title: 'Me Llama: Foundation Large Language Models For Medical Applications'
authors: Xie Qianqian, Chen Qingyu, Chen Aokun, Peng Cheng, Hu Yan, Lin Fongci, Peng Xueqing, Huang Jimin, Zhang Jeffrey, Keloth Vipina, Zhou Xinyu, He Huan, Ohno-machado Lucila, Wu Yonghui, Xu Hua, Bian Jiang
conference: "Arxiv"
year: 2024
bibkey: xie2024me
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12749"}
  - {name: "Code", url: "https://github.com/BIDS-Xu-Lab/Me-LLaMA"}
tags: ['Applications', 'Few Shot', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
"Recent advancements in large language models (LLMs) such as ChatGPT and LLaMA have hinted at their potential to revolutionize medical applications, yet their application in clinical settings often reveals limitations due to a lack of specialized training on medical-specific data. In response to this challenge, this study introduces Me-LLaMA, a novel medical LLM family that includes foundation models - Me-LLaMA 13/70B, along with their chat-enhanced versions - Me-LLaMA 13/70B-chat, developed through continual pre-training and instruction tuning of LLaMA2 using large medical datasets. Our methodology leverages a comprehensive domain-specific data suite, including a large-scale, continual pre-training dataset with 129B tokens, an instruction tuning dataset with 214k samples, and a new medical evaluation benchmark (MIBE) across six critical medical tasks with 12 datasets. Our extensive evaluation using the MIBE shows that Me-LLaMA models achieve overall better performance than existing open-source medical LLMs in zero-shot, few-shot and supervised learning abilities. With task-specific instruction tuning, Me-LLaMA models outperform ChatGPT on 7 out of 8 datasets and GPT-4 on 5 out of 8 datasets. In addition, we investigated the catastrophic forgetting problem, and our results show that Me-LLaMA models outperform other open-source medical LLMs in mitigating this issue. Me-LLaMA is one of the largest open-source medical foundation LLMs that use both biomedical and clinical data. It exhibits superior performance across both general and medical tasks compared to other open-source medical LLMs, rendering it an attractive choice for medical AI applications. We release our models, datasets, and evaluation scripts at: https://github.com/BIDS-Xu-Lab/Me-LLaMA."
