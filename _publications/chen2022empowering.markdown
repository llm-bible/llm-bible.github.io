---
layout: publication
title: Empowering Parameter45;efficient Transfer Learning By Recognizing The Kernel Structure In Self45;attention
authors: Chen Yifan, Hazarika Devamanyu, Namazifar Mahdi, Liu Yang, Jin Di, Hakkani-tur Dilek
conference: "Arxiv"
year: 2022
bibkey: chen2022empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.03720"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The massive amount of trainable parameters in the pre45;trained language models (PLMs) makes them hard to be deployed to multiple downstream tasks. To address this issue parameter45;efficient transfer learning methods have been proposed to tune only a few parameters during fine45;tuning while freezing the rest. This paper looks at existing methods along this line through the textit123;kernel lens125;. Motivated by the connection between self45;attention in transformer45;based PLMs and kernel learning we propose textit123;kernel45;wise adapters125; namely textit123;Kernel45;mix125; that utilize the kernel structure in self45;attention to guide the assignment of the tunable parameters. These adapters use guidelines found in classical kernel learning and enable separate parameter tuning for each attention head. Our empirical results over a diverse set of natural language generation and understanding tasks show that our proposed adapters can attain or improve the strong performance of existing baselines.
