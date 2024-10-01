---
layout: publication
title: 'Toolbehonest: A Multi-level Hallucination Diagnostic Benchmark For Tool-augmented Large Language Models'
authors: Zhang Yuxiang, Chen Jing, Wang Junjie, Liu Yaxin, Yang Cheng, Shi Chufan, Zhu Xinyu, Lin Zihao, Wan Hanwen, Yang Yujiu, Sakai Tetsuya, Feng Tian, Yamana Hayato
conference: "Arxiv"
year: 2024
bibkey: zhang2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20015"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Tool-augmented large language models (LLMs) are rapidly being integrated into real-world applications. Due to the lack of benchmarks, the community still needs to fully understand the hallucination issues within these models. To address this challenge, we introduce a comprehensive diagnostic benchmark, ToolBH. Specifically, we assess the LLM's hallucinations through two perspectives: depth and breadth. In terms of depth, we propose a multi-level diagnostic process, including (1) solvability detection, (2) solution planning, and (3) missing-tool analysis. For breadth, we consider three scenarios based on the characteristics of the toolset: missing necessary tools, potential tools, and limited functionality tools. Furthermore, we developed seven tasks and collected 700 evaluation samples through multiple rounds of manual annotation. The results show the significant challenges presented by the ToolBH benchmark. The current advanced models Gemini-1.5-Pro and GPT-4o only achieve a total score of 45.3 and 37.0, respectively, on a scale of 100. In this benchmark, larger model parameters do not guarantee better performance; the training data and response strategies also play a crucial role in tool-enhanced LLM scenarios. Our diagnostic analysis indicates that the primary reason for model errors lies in assessing task solvability. Additionally, open-weight models suffer from performance drops with verbose replies, whereas proprietary models excel with longer reasoning.
