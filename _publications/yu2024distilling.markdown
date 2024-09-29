---
layout: publication
title: 'Distilling System 2 Into System 1'
authors: Yu Ping, Xu Jing, Weston Jason, Kulikov Ilia
conference: "Arxiv"
year: 2024
bibkey: yu2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06023"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) can spend extra compute during inference to generate intermediate thoughts which helps to produce better final responses. Since Chain-of-Thought (Wei et al. 2022) many such System 2 techniques have been proposed such as Rephrase and Respond (Deng et al. 2023a) System 2 Attention (Weston and Sukhbaatar 2023) and Branch-Solve-Merge (Saha et al. 2023). In this work we investigate self-supervised methods to compile (distill) higher quality outputs from System 2 techniques back into LLM generations without intermediate reasoning token sequences as this reasoning has been distilled into System 1. We show that several such techniques can be successfully distilled resulting in improved results compared to the original System 1 performance and with less inference cost than System 2. We posit that such System 2 distillation will be an important feature of future continually learning AI systems enabling them to focus System 2 capabilities on the reasoning tasks that they cannot yet do well.
