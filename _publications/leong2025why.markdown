---
layout: publication
title: 'Why Safeguarded Ships Run Aground? Aligned Large Language Models'' Safety Mechanisms Tend To Be Anchored In The Template Region'
authors: Chak Tou Leong, Qingyu Yin, Jian Wang, Wenjie Li
conference: "Arxiv"
year: 2025
bibkey: leong2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13946'}
tags: ['Reinforcement Learning', 'RAG', 'Security', 'Responsible AI']
---
The safety alignment of large language models (LLMs) remains vulnerable, as their initial behavior can be easily jailbroken by even relatively simple attacks. Since infilling a fixed template between the input instruction and initial model output is a common practice for existing LLMs, we hypothesize that this template is a key factor behind their vulnerabilities: LLMs' safety-related decision-making overly relies on the aggregated information from the template region, which largely influences these models' safety behavior. We refer to this issue as template-anchored safety alignment. In this paper, we conduct extensive experiments and verify that template-anchored safety alignment is widespread across various aligned LLMs. Our mechanistic analyses demonstrate how it leads to models' susceptibility when encountering inference-time jailbreak attacks. Furthermore, we show that detaching safety mechanisms from the template region is promising in mitigating vulnerabilities to jailbreak attacks. We encourage future research to develop more robust safety alignment techniques that reduce reliance on the template region.
