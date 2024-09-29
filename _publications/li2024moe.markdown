---
layout: publication
title: Moe45;ct A Novel Approach For Large Language Models Training With Resistance To Catastrophic Forgetting
authors: Li Tianhao, Li Shangjie, Xie Binbin, Xiong Deyi, Yang Baosong
conference: "Arxiv"
year: 2024
bibkey: li2024moe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00875"}
tags: ['Fine Tuning', 'Language Modeling', 'Model Architecture', 'Tools', 'Training Techniques']
---
The advent of large language models (LLMs) has predominantly catered to high45;resource languages leaving a disparity in performance for low45;resource languages. Conventional Continual Training (CT) approaches to bridge this gap often undermine a models original linguistic proficiency when expanding to multilingual contexts. Addressing this issue we introduce a novel MoE45;CT architecture a paradigm that innovatively separates the base models learning from the multilingual expansion process. Our design freezes the original LLM parameters thus safeguarding its performance in high45;resource languages while an appended MoE module trained on diverse language datasets augments low45;resource language proficiency. Our approach significantly outperforms conventional CT methods as evidenced by our experiments which show marked improvements in multilingual benchmarks without sacrificing the models original language performance. Moreover our MoE45;CT framework demonstrates enhanced resistance to forgetting and superior transfer learning capabilities. By preserving the base models integrity and focusing on strategic parameter expansion our methodology advances multilingual language modeling and represents a significant step forward for low45;resource language inclusion in LLMs indicating a fruitful direction for future research in language technologies.
