---
layout: publication
title: 'Large Language Models For Tuning Evolution Strategies'
authors: Kramer Oliver
conference: "Arxiv"
year: 2024
bibkey: kramer2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10999"}
tags: ['Applications', 'Efficiency And Optimization', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) exhibit world knowledge and inference capabilities, making them powerful tools for various applications. This paper proposes a feedback loop mechanism that leverages these capabilities to tune Evolution Strategies (ES) parameters effectively. The mechanism involves a structured process of providing programming instructions, executing the corresponding code, and conducting thorough analysis. This process is specifically designed for the optimization of ES parameters. The method operates through an iterative cycle, ensuring continuous refinement of the ES parameters. First, LLMs process the instructions to generate or modify the code. The code is then executed, and the results are meticulously logged. Subsequent analysis of these results provides insights that drive further improvements. An experiment on tuning the learning rates of ES using the LLaMA3 model demonstrate the feasibility of this approach. This research illustrates how LLMs can be harnessed to improve ES algorithms' performance and suggests broader applications for similar feedback loop mechanisms in various domains.
