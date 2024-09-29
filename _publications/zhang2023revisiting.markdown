---
layout: publication
title: Revisiting Block45;based Quantisation What Is Important For Sub45;845;bit LLM Inference
authors: Zhang Cheng, Cheng Jianyi, Shumailov Ilia, Constantinides George A., Zhao Yiren
conference: "Arxiv"
year: 2023
bibkey: zhang2023revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05079"}
tags: ['Efficiency And Optimization', 'Reinforcement Learning', 'Training Techniques']
---
The inference of Large language models (LLMs) requires immense computation and memory resources. To curtail these costs quantisation has merged as a promising solution but existing LLM quantisation mainly focuses on 845;bit. In this work we explore the statistical and learning properties of the LLM layer and attribute the bottleneck of LLM quantisation to numerical scaling offsets. To address this we adapt block quantisations for LLMs a family of methods that share scaling factors across packed numbers. Block quantisations efficiently reduce the numerical scaling offsets solely from an arithmetic perspective without additional treatments in the computational path. Our nearly45;lossless quantised 645;bit LLMs achieve a 19× higher arithmetic density and 5× memory density than the float32 baseline surpassing the prior art 845;bit quantisation by 2.5× in arithmetic density and 1.2× in memory density without requiring any data calibration or re45;training. We also share our insights into sub45;845;bit LLM quantisation including the mismatch between activation and weight distributions optimal fine45;tuning strategies and a lower quantisation granularity inherent in the statistical properties of LLMs. The latter two tricks enable nearly45;lossless 445;bit LLMs on downstream tasks. Our code is open45;sourced.
