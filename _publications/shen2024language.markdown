---
layout: publication
title: The Language Barrier Dissecting Safety Challenges Of Llms In Multilingual Contexts
authors: Shen Lingfeng, Tan Weiting, Chen Sihao, Chen Yunmo, Zhang Jingyu, Xu Haoran, Zheng Boyuan, Koehn Philipp, Khashabi Daniel
conference: "Arxiv"
year: 2024
bibkey: shen2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13136"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
As the influence of large language models (LLMs) spans across global communities their safety challenges in multilingual settings become paramount for alignment research. This paper examines the variations in safety challenges faced by LLMs across different languages and discusses approaches to alleviating such concerns. By comparing how state45;of45;the45;art LLMs respond to the same set of malicious prompts written in higher45; vs. lower45;resource languages we observe that (1) LLMs tend to generate unsafe responses much more often when a malicious prompt is written in a lower45;resource language and (2) LLMs tend to generate more irrelevant responses to malicious prompts in lower45;resource languages. To understand where the discrepancy can be attributed we study the effect of instruction tuning with reinforcement learning from human feedback (RLHF) or supervised finetuning (SFT) on the HH45;RLHF dataset. Surprisingly while training with high45;resource languages improves model alignment training in lower45;resource languages yields minimal improvement. This suggests that the bottleneck of cross45;lingual alignment is rooted in the pretraining stage. Our findings highlight the challenges in cross45;lingual LLM safety and we hope they inform future research in this direction.
