---
layout: publication
title: TPD Enhancing Student Language Model Reasoning Via Principle Discovery And Guidance
authors: Wang Haorui, Zhang Rongzhi, Li Yinghao, Kong Lingkai, Zhuang Yuchen, Chen Xiusi, Zhang Chao
conference: "Arxiv"
year: 2024
bibkey: wang2024tpd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13849"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have recently showcased remarkable reasoning abilities. However larger models often surpass their smaller counterparts in reasoning tasks posing the challenge of effectively transferring these capabilities from larger models. Existing approaches heavily rely on extensive fine-tuning data or continuous interactions with a superior teacher LLM during inference. We introduce a principle-based teacher-student framework called Teaching via Principle Discovery (TPD) to address these limitations. Inspired by human learning mechanisms TPD mimics the interaction between a teacher and a student using a principle-based approach. The teacher LLM generates problem-solving instructions and corrective principles based on the student LLMs errors. These principles guide the refinement of instructions and the selection of instructive examples from a validation set. This enables the student model to learn from both the teachers guidance and its own mistakes. Once the student model begins making inferences TPD requires no further intervention from the teacher LLM or humans. Through extensive experiments across eight reasoning tasks we demonstrate the effectiveness of TPD. Compared to standard chain-of-thought prompting TPD significantly improves the student models performance achieving 6.237; improvement on average.
