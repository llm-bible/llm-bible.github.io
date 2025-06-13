---
layout: publication
title: 'Wingpt-3.0 Technical Report'
authors: Boqin Zhuang, Chenxiao Song, Huitong Lu, Jiacheng Qiao, Mingqian Liu, Mingxing Yu, Ping Hong, Rui Li, Xiaoxia Song, Xiangjun Xu, Xu Chen, Yaoyao Ma, Yujie Gao
conference: "Arxiv"
year: 2025
bibkey: zhuang2025wingpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17387"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Current Large Language Models (LLMs) exhibit significant limitations, notably in structured, interpretable, and verifiable medical reasoning, alongside practical deployment challenges related to computational resources and data privacy. This report focused on the development of WiNGPT-3.0, the 32-billion parameter LLMs, engineered with the objective of enhancing its capacity for medical reasoning and exploring its potential for effective integration within healthcare IT infrastructures. The broader aim is to advance towards clinically applicable models. The approach involved a multi-stage training pipeline tailored for general, medical, and clinical reasoning. This pipeline incorporated supervised fine-tuning (SFT) and reinforcement learning (RL), leveraging curated Long Chain-of-Thought (CoT) datasets, auxiliary reward models, and an evidence-based diagnostic chain simulation. WiNGPT-3.0 demonstrated strong performance: specific model variants achieved scores of 66.6 on MedCalc and 87.1 on MedQA-USMLE. Furthermore, targeted training improved performance on a clinical reasoning task from a baseline score of 58.1 to 62.5. These findings suggest that reinforcement learning, even when applied with a limited dataset of only a few thousand examples, can enhance medical reasoning accuracy. Crucially, this demonstration of RL's efficacy with limited data and computation paves the way for more trustworthy and practically deployable LLMs within clinical workflows and health information infrastructures.
