---
layout: publication
title: 'Qilin-med: Multi-stage Knowledge Injection Advanced Medical Large Language Model'
authors: Qichen Ye, Junling Liu, Dading Chong, Peilin Zhou, Yining Hua, Fenglin Liu, Meng Cao, Ziming Wang, Xuxin Cheng, Zhu Lei, Zhenhua Guo
conference: "Arxiv"
year: 2023
bibkey: ye2023qilin
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09089"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Integrating large language models (LLMs) into healthcare holds great
potential but faces challenges. Pre-training LLMs from scratch for domains like
medicine is resource-heavy and often unfeasible. On the other hand, sole
reliance on Supervised Fine-tuning (SFT) can result in overconfident
predictions and may not tap into domain-specific insights. In response, we
present a multi-stage training method combining Domain-specific Continued
Pre-training (DCPT), SFT, and Direct Preference Optimization (DPO). In
addition, we publish a 3Gb Chinese Medicine (ChiMed) dataset, encompassing
medical question answering, plain texts, knowledge graphs, and dialogues,
segmented into three training stages. The medical LLM trained with our
pipeline, Qilin-Med, shows substantial performance improvement. In the CPT and
SFT phases, Qilin-Med achieved 38.4% and 40.0% accuracy on the CMExam test set,
respectively. It outperformed the basemodel Baichuan-7B (accuracy: 33.5%), by
7.5%. In the DPO phase, it scored 16.66 in BLEU-1 and 27.44 in ROUGE-1 on the
Huatuo-26M test set, bringing further improvement to the SFT phase (12.69 in
BLEU-1 and 24.21 in ROUGE-1). Additionally, we have further enhanced the
model's performance through the Retrieval Augmented Generation (RAG) approach.
Experiments demonstrate that Qilin-Med-RAG achieves an accuracy rate of 42.8%
on CMExam. These results highlight the contribution of our novel training
approach in building LLMs for medical applications.
