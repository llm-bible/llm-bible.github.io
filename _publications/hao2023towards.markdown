---
layout: publication
title: 'Towards Efficient Vision-language Tuning: More Information Density, More Generalizability'
authors: Tianxiang Hao, Mengyao Lyu, Hui Chen, Sicheng Zhao, Xiaohan Ding, Jungong Han, Guiguang Ding
conference: "Arxiv"
year: 2023
bibkey: hao2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10813"}
tags: ['Security', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
With the advancement of large pre-trained vision-language models, effectively
transferring the knowledge embedded within these foundational models to
downstream tasks has become a pivotal topic, particularly in data-scarce
environments. Recently, parameter-efficient fine-tuning approaches, especially
prompt tuning, have garnered considerable attention. To better understand the
nature of prompt tuning, we propose the concept of ``Information Density'' (ID)
to indicate whether a matrix strongly belongs to certain feature spaces rather
than being evenly distributed across various feature spaces. We suppose a
higher ID with strong bias across some feature spaces naturally leads to
excellent robustness and stability. Our research, inspired by the observation
that generalizability is closely linked to the information density of the
prompt matrix, introduces the Dense Information Prompt (DIP). DIP aims to
enhance information density to improve generalization. Furthermore, DIP
significantly reduces the number of tunable parameters and the requisite
storage space, making it particularly advantageous in resource-constrained
settings. Comprehensive experiments substantiate the superiority of DIP.
Notably, DIP surpasses the latest state-of-the-art methods by a substantial
margin with an exceptionally small parameter count. Across a range of tasks
spanning 11 datasets, DIP improves the average downstream accuracy of classic
prompt tuning by up to 5.76% using merely 0.5K parameters.
