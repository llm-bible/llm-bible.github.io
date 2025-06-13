---
layout: publication
title: 'Have The Vlms Lost Confidence? A Study Of Sycophancy In Vlms'
authors: Shuo Li, Tao Ji, Xiaoran Fan, Linsheng Lu, Leyi Yang, Yuming Yang, Zhiheng Xi, Rui Zheng, Yuran Wang, Xiaohui Zhao, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: li2024have
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11302"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
In the study of LLMs, sycophancy represents a prevalent hallucination that
poses significant challenges to these models. Specifically, LLMs often fail to
adhere to original correct responses, instead blindly agreeing with users'
opinions, even when those opinions are incorrect or malicious. However,
research on sycophancy in visual language models (VLMs) has been scarce. In
this work, we extend the exploration of sycophancy from LLMs to VLMs,
introducing the MM-SY benchmark to evaluate this phenomenon. We present
evaluation results from multiple representative models, addressing the gap in
sycophancy research for VLMs. To mitigate sycophancy, we propose a synthetic
dataset for training and employ methods based on prompts, supervised
fine-tuning, and DPO. Our experiments demonstrate that these methods
effectively alleviate sycophancy in VLMs. Additionally, we probe VLMs to assess
the semantic impact of sycophancy and analyze the attention distribution of
visual tokens. Our findings indicate that the ability to prevent sycophancy is
predominantly observed in higher layers of the model. The lack of attention to
image knowledge in these higher layers may contribute to sycophancy, and
enhancing image attention at high layers proves beneficial in mitigating this
issue.
