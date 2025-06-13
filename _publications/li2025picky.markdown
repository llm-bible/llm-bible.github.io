---
layout: publication
title: 'Picky Llms And Unreliable Rms: An Empirical Study On Safety Alignment After Instruction Tuning'
authors: Guanlin Li, Kangjie Chen, Shangwei Guo, Jie Zhang, Han Qiu, Chao Zhang, Guoyin Wang, Tianwei Zhang, Jiwei Li
conference: "Arxiv"
year: 2025
bibkey: li2025picky
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01116"}
  - {name: "Code", url: "https://github.com/GuanlinLee/llm_instruction_tuning"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have emerged as powerful tools for addressing a
wide range of general inquiries and tasks. Despite this, fine-tuning aligned
LLMs on smaller, domain-specific datasets, critical to adapting them to
specialized tasks, can inadvertently degrade their safety alignment, even when
the datasets are benign. This phenomenon makes models more susceptible to
providing inappropriate responses. In this study, we systematically examine the
factors contributing to safety alignment degradation in benign fine-tuning
scenarios. Our analysis identifies three critical factors affecting aligned
LLMs: answer structure, identity calibration, and role-play. Additionally, we
evaluate the reliability of state-of-the-art reward models (RMs), which are
often used to guide alignment processes. Our findings reveal that these RMs
frequently fail to accurately reflect human preferences regarding safety,
underscoring their limitations in practical applications. By uncovering these
challenges, our work highlights the complexities of maintaining safety
alignment during fine-tuning and offers guidance to help developers balance
utility and safety in LLMs. Datasets and fine-tuning code used in our
experiments can be found in
https://github.com/GuanlinLee/llm_instruction_tuning.
