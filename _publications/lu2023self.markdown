---
layout: publication
title: 'SELF: Self-evolution With Language Feedback'
authors: Lu Jianqiao, Zhong Wanjun, Huang Wenyong, Wang Yufei, Zhu Qi, Mi Fei, Wang Baojun, Wang Weichao, Zeng Xingshan, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2023
bibkey: lu2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00533"}
tags: ['Pretraining Methods', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable versatility across various domains. To further advance LLMs we propose SELF (Self-Evolution with Language Feedback) a novel approach that enables LLMs to self-improve through self-reflection akin to human learning processes. SELF initiates with a meta-skill learning process that equips the LLMs with capabilities for self-feedback and self-refinement. Subsequently the model undergoes an iterative process of self-evolution. In each iteration it utilizes an unlabeled dataset of instructions to generate initial responses. These responses are enhanced through self-feedback and self-refinement. The model is then fine-tuned using this enhanced data. The model undergoes progressive improvement through this iterative self-evolution process. Moreover the SELF framework enables the model to apply self-refinement during inference which further improves response quality. Our experiments in mathematics and general tasks demonstrate that SELF can enhance the capabilities of LLMs without human intervention. The SELF framework indicates a promising direction for the autonomous evolution of LLMs transitioning them from passive information receivers to active participants in their development.
