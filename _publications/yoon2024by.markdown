---
layout: publication
title: 'By My Eyes: Grounding Multimodal Large Language Models With Sensor Data Via Visual Prompting'
authors: Hyungjun Yoon, Biniyam Aschalew Tolera, Taesik Gong, Kimin Lee, Sung-ju Lee
conference: "Arxiv"
year: 2024
bibkey: yoon2024by
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.10385'}
  - {name: "Code", url: 'https://github.com/diamond264/ByMyEyes'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Applications', 'Prompting', 'Multimodal Models']
---
Large language models (LLMs) have demonstrated exceptional abilities across
various domains. However, utilizing LLMs for ubiquitous sensing applications
remains challenging as existing text-prompt methods show significant
performance degradation when handling long sensor data sequences. We propose a
visual prompting approach for sensor data using multimodal LLMs (MLLMs). We
design a visual prompt that directs MLLMs to utilize visualized sensor data
alongside the target sensory task descriptions. Additionally, we introduce a
visualization generator that automates the creation of optimal visualizations
tailored to a given sensory task, eliminating the need for prior task-specific
knowledge. We evaluated our approach on nine sensory tasks involving four
sensing modalities, achieving an average of 10% higher accuracy than text-based
prompts and reducing token costs by 15.8 times. Our findings highlight the
effectiveness and cost-efficiency of visual prompts with MLLMs for various
sensory tasks. The source code is available at
https://github.com/diamond264/ByMyEyes.
