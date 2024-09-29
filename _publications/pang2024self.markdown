---
layout: publication
title: Self45;alignment Of Large Language Models Via Monopolylogue45;based Social Scene Simulation
authors: Pang Xianghe, Tang Shuo, Ye Rui, Xiong Yuxin, Zhang Bolun, Wang Yanfeng, Chen Siheng
conference: "Arxiv"
year: 2024
bibkey: pang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05699"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Tools']
---
Aligning large language models (LLMs) with human values is imperative to mitigate potential adverse effects resulting from their misuse. Drawing from the sociological insight that acknowledging all parties concerns is a key factor in shaping human values this paper proposes a novel direction to align LLMs by themselves social scene simulation. To achieve this we present MATRIX a novel social scene simulator that emulates realistic scenes around a users input query enabling the LLM to take social consequences into account before responding. MATRIX serves as a virtual rehearsal space akin to a Monopolylogue where the LLM performs diverse roles related to the query and practice by itself. To inject this alignment we fine45;tune the LLM with MATRIX45;simulated data ensuring adherence to human values without compromising inference speed. We theoretically show that the LLM with MATRIX outperforms Constitutional AI under mild assumptions. Finally extensive experiments validate that our method outperforms over 10 baselines across 4 benchmarks. As evidenced by 875 user ratings our tuned 13B45;size LLM exceeds GPT45;4 in aligning with human values. See our project page at https://shuotang123.github.io/MATRIX.
