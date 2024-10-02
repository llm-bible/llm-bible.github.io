---
layout: publication
title: 'Rotbench: A Multi-level Benchmark For Evaluating The Robustness Of Large Language Models In Tool Learning'
authors: Ye Junjie, Wu Yilong, Gao Songyang, Huang Caishuang, Li Sixian, Li Guanyu, Fan Xiaoran, Zhang Qi, Gui Tao, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: ye2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08326"}
  - {name: "Code", url: "https://github.com/Junjie-Ye/RoTBench"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
'Tool learning has generated widespread interest as a vital means of interaction between Large Language Models (LLMs) and the physical world. Current research predominantly emphasizes LLMs'' capacity to utilize tools in well-structured environments while overlooking their stability when confronted with the inevitable noise of the real world. To bridge this gap, we introduce RoTBench, a multi-level benchmark for evaluating the robustness of LLMs in tool learning. Specifically, we establish five external environments, each featuring varying levels of noise (i.e., Clean, Slight, Medium, Heavy, and Union), providing an in-depth analysis of the model''s resilience across three critical phases: tool selection, parameter identification, and content filling. Experiments involving six widely-used models underscore the urgent necessity for enhancing the robustness of LLMs in tool learning. For instance, the performance of GPT-4 even drops significantly from 80.00 to 58.10 when there is no substantial change in manual accuracy. More surprisingly, the noise correction capability inherent in the GPT family paradoxically impedes its adaptability in the face of mild noise. In light of these findings, we propose RoTTuning, a strategy that enriches the diversity of training environments to bolster the robustness of LLMs in tool learning. The code and data are available at https://github.com/Junjie-Ye/RoTBench.'
