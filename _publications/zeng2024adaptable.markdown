---
layout: publication
title: 'Adaptable And Precise: Enterprise-scenario LLM Function-calling Capability Training Pipeline'
authors: Guancheng Zeng, Wentao Ding, Beining Xu, Chi Zhang, Wenqiang Han, Gang Li, Jingjing Mo, Pengxu Qiu, Xinran Tao, Wang Tao, Haowen Hu
conference: "Arxiv"
year: 2024
bibkey: zeng2024adaptable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15660"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Enterprises possess a vast array of API assets scattered across various
functions, forming the backbone of existing business processes. By leveraging
these APIs as functional tools, enterprises can design diverse,
scenario-specific agent applications, driven by on-premise function-calling
models as the core engine. However, generic models often fail to meet
enterprise requirements in terms of computational efficiency, output accuracy,
and stability, necessitating scenario-specific adaptation. In this paper, we
propose a training pipeline for function-calling capabilities tailored to
real-world business scenarios. This pipeline includes the synthesis and
augmentation of scenario-specific function-calling data, model fine-tuning, and
performance evaluation and analysis. Using this pipeline, we generated 1,260
fully AI-generated samples and 1,035 augmented manually-labeled samples in
digital HR agent scenario. The Qwen2.5-Coder-7B-Instruct model was employed as
the base model and fine-tuned using the LoRA method on four GPUs with 24GB
VRAM. Our fine-tuned model demonstrated outstanding performance in evaluations
and practical applications, surpassing GPT-4 and GPT-4o in accuracy on the test
set. These results validate the reliability of the proposed pipeline for
training scenario-specific function-calling models.
