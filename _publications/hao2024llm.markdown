---
layout: publication
title: LLM Reasoners New Evaluation Library And Analysis Of Step45;by45;step Reasoning With Large Language Models
authors: Hao Shibo, Gu Yi, Luo Haotian, Liu Tianyang, Shao Xiyan, Wang Xinyuan, Xie Shuhua, Ma Haodi, Samavedhi Adithya, Gao Qiyue, Wang Zhen, Hu Zhiting
conference: "Arxiv"
year: 2024
bibkey: hao2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05221"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
Generating accurate step45;by45;step reasoning is essential for Large Language Models (LLMs) to address complex problems and enhance robustness and interpretability. Despite the flux of research on developing advanced reasoning approaches systematically analyzing the diverse LLMs and reasoning strategies in generating reasoning chains remains a significant challenge. The difficulties stem from the lack of two key elements (1) an automatic method for evaluating the generated reasoning chains on different tasks and (2) a unified formalism and implementation of the diverse reasoning approaches for systematic comparison. This paper aims to close the gap (1) We introduce AutoRace for fully automated reasoning chain evaluation. Existing metrics rely on expensive human annotations or pre45;defined LLM prompts not adaptable to different tasks. In contrast AutoRace automatically creates detailed evaluation criteria tailored for each task and uses GPT45;4 for accurate evaluation following the criteria. (2) We develop LLM Reasoners a library for standardized modular implementation of existing and new reasoning algorithms under a unified formulation of the search reward and world model components. With the new evaluation and library (3) we conduct extensive study of different reasoning approaches (e.g. CoT ToT RAP). The analysis reveals interesting findings about different factors contributing to reasoning including the reward45;guidance breadth45;vs45;depth in search world model and prompt formats etc.
