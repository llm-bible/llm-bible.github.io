---
layout: publication
title: Accelerating Greedy Coordinate Gradient via Probe Sampling
authors: Zhao Yiran, Zheng Wenyue, Cai Tianle, Do Xuan Long, Kawaguchi Kenji, Goyal Anirudh, Shieh Michael
conference: "Arxiv"
year: 2024
bibkey: zhao2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01251"}
tags: ['Efficiency And Optimization', 'Prompting', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
Safety of Large Language Models (LLMs) has become a critical issue given their rapid progresses. Greedy Coordinate Gradient (GCG) is shown to be effective in constructing adversarial prompts to break the aligned LLMs but optimization of GCG is time-consuming. To reduce the time cost of GCG and enable more comprehensive studies of LLM safety in this work we study a new algorithm called . At the core of the algorithm is a mechanism that dynamically determines how similar a smaller draft models predictions are to the target models predictions for prompt candidates. When the target model is similar to the draft model we rely heavily on the draft model to filter out a large number of potential prompt candidates. Probe sampling achieves up to 5.6 times speedup using Llama2-7b-chat and leads to equal or improved attack success rate (ASR) on the AdvBench. Furthermore probe sampling is also able to accelerate other prompt optimization techniques and adversarial methods leading to acceleration of 1.8times for AutoPrompt 2.4times for APE and 2.4times for AutoDAN.
