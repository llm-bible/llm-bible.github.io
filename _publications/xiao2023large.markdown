---
layout: publication
title: 'Privacymind: Large Language Models Can Be Contextual Privacy Protection Learners'
authors: Yijia Xiao, Yiqiao Jin, Yushi Bai, Yue Wu, Xianjun Yang, Xiao Luo, Wenchao Yu, Xujiang Zhao, Yanchi Liu, Quanquan Gu, Haifeng Chen, Wei Wang, Wei Cheng
conference: "Arxiv"
year: 2023
bibkey: xiao2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02469"}
  - {name: "Code", url: "https://github.com/Yijia-Xiao/PrivacyMind"}
tags: ['Fine-Tuning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The proliferation of Large Language Models (LLMs) has driven considerable
interest in fine-tuning them with domain-specific data to create specialized
language models. Nevertheless, such domain-specific fine-tuning data often
contains contextually sensitive personally identifiable information (PII).
Direct fine-tuning of LLMs on this data without privacy protection poses a risk
of data leakage of sensitive PII during inference time. To address this
challenge, we introduce Contextual Privacy Protection Language Models
(PrivacyMind), a novel paradigm for fine-tuning LLMs that effectively injects
domain-specific knowledge while safeguarding inference-time data privacy. Our
work offers a theoretical analysis for model design and benchmarks various
techniques such as corpus curation, penalty-based unlikelihood in training
loss, instruction-based tuning, etc. Extensive experiments across diverse
datasets and scenarios demonstrate the effectiveness of our approaches. In
particular, instruction tuning with both positive and negative examples stands
out as a promising method, effectively protecting private data while enhancing
the model's knowledge. Our work underscores the potential for Large Language
Models as robust contextual privacy protection learners. The complete code and
data for the work can be found at https://github.com/Yijia-Xiao/PrivacyMind.
