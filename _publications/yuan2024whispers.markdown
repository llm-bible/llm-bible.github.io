---
layout: publication
title: 'Whispers That Shake Foundations: Analyzing And Mitigating False Premise Hallucinations In Large Language Models'
authors: Yuan Hongbang, Cao Pengfei, Jin Zhuoran, Chen Yubo, Zeng Daojian, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: yuan2024whispers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.19103"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have shown impressive capabilities but still
suffer from the issue of hallucinations. A significant type of this issue is
the false premise hallucination, which we define as the phenomenon when LLMs
generate hallucinated text when confronted with false premise questions. In
this paper, we perform a comprehensive analysis of the false premise
hallucination and elucidate its internal working mechanism: a small subset of
attention heads (which we designate as false premise heads) disturb the
knowledge extraction process, leading to the occurrence of false premise
hallucination. Based on our analysis, we propose \textbf\{FAITH\} (\textbf\{F\}alse
premise \textbf\{A\}ttention head constra\textbf\{I\}ining for mi\textbf\{T\}igating
\textbf\{H\}allucinations), a novel and effective method to mitigate false
premise hallucinations. It constrains the false premise attention heads during
the model inference process. Impressively, extensive experiments demonstrate
that constraining only approximately \\(1%\\) of the attention heads in the model
yields a notable increase of nearly \\(20%\\) of model performance.
