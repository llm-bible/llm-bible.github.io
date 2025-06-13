---
layout: publication
title: 'Mentalmac: Enhancing Large Language Models For Detecting Mental Manipulation Via Multi-task Anti-curriculum Distillation'
authors: Yuansheng Gao, Han Bao, Tong Zhang, Bin Li, Zonghui Wang, Wenzhi Chen
conference: "Arxiv"
year: 2025
bibkey: gao2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15255'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Distillation', 'Training Techniques']
---
Mental manipulation is a subtle yet pervasive form of psychological abuse that poses serious threats to mental health. Its covert nature and the complexity of manipulation strategies make it challenging to detect, even for state-of-the-art large language models (LLMs). This concealment also hinders the manual collection of large-scale, high-quality annotations essential for training effective models. Although recent efforts have sought to improve LLMs' performance on this task, progress remains limited due to the scarcity of real-world annotated datasets. To address these challenges, we propose MentalMAC, a multi-task anti-curriculum distillation method that enhances LLMs' ability to detect mental manipulation in multi-turn dialogue. Our approach includes: (i) EvoSA, an unsupervised data expansion method based on evolutionary operations and speech act theory; (ii) teacher model-generated multi-task supervision; and (iii) progressive knowledge distillation from complex to simpler tasks. We then constructed the ReaMent dataset with 5,000 real-world dialogue samples, using a MentalMAC-distilled model to assist human annotation. Vast experiments demonstrate that our method significantly narrows the gap between student and teacher models and outperforms competitive LLMs across key evaluation metrics. All code, datasets, and checkpoints will be released upon paper acceptance. Warning: This paper contains content that may be offensive to readers.
