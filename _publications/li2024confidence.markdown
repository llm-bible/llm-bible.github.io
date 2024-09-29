---
layout: publication
title: 'Confidence Matters: Revisiting Intrinsic Self-correction Capabilities Of Large Language Models'
authors: Li Loka, Chen Zhenhao, Chen Guangyi, Zhang Yixuan, Su Yusheng, Xing Eric, Zhang Kun
conference: "Arxiv"
year: 2024
bibkey: li2024confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12563"}
  - {name: "Code", url: "https://github.com/MBZUAI-CLeaR/IoE-Prompting.git"}
tags: ['Has Code', 'Prompting', 'Reinforcement Learning', 'Tools']
---
The recent success of Large Language Models (LLMs) has catalyzed an increasing interest in their self-correction capabilities. This paper presents a comprehensive investigation into the intrinsic self-correction of LLMs attempting to address the ongoing debate about its feasibility. Our research has identified an important latent factor - the confidence of LLMs - during the self-correction process. Overlooking this factor may cause the models to over-criticize themselves resulting in unreliable conclusions regarding the efficacy of self-correction. We have experimentally observed that LLMs possess the capability to understand the confidence in their own responses. It motivates us to develop an If-or-Else (IoE) prompting framework designed to guide LLMs in assessing their own confidence facilitating intrinsic self-corrections. We conduct extensive experiments and demonstrate that our IoE-based Prompt can achieve a consistent improvement regarding the accuracy of self-corrected responses over the initial answers. Our study not only sheds light on the underlying factors affecting self-correction in LLMs but also introduces a practical framework that utilizes the IoE prompting principle to efficiently improve self-correction capabilities with confidence. The code is available at https://github.com/MBZUAI-CLeaR/IoE-Prompting.git."
