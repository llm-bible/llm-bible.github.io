---
layout: publication
title: MARIO Math Reasoning With Code Interpreter Output 45;45; A Reproducible Pipeline
authors: Liao Minpeng, Luo Wei, Li Chengxi, Wu Jing, Fan Kai
conference: "Arxiv"
year: 2024
bibkey: liao2024math
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08190"}
  - {name: "Code", url: "https://github.com/MARIO&#45;Math&#45;Reasoning/MARIO&#125;"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper', 'Training Techniques']
---
Large language models (LLMs) have seen considerable advancements in natural language understanding tasks yet there remains a gap to bridge before attaining true artificial general intelligence especially concerning shortcomings in mathematical reasoning capabilities. We postulate that the inherent nature of LLM training which focuses on predicting probabilities of next token presents challenges in effectively modeling mathematical reasoning that demands exact calculations both from data45;driven and theoretical standpoints. In this paper we address this challenge by enriching the data landscape and introducing a novel math dataset enhanced with a capability to utilize a Python code interpreter. This dataset is derived from GSM8K and MATH and has been further refined through a combination of GPT45;4 annotations human review and self45;training processes where the errors in the original GSM8K training set have been fixed. Additionally we propose a tentative easily replicable protocol for the fine45;tuning of math45;specific LLMs which has led to a significant improvement in the performance of a 7B45;parameter LLM on the GSM8K and MATH datasets. We are committed to advancing the field of mathematical reasoning in LLMs and to that end we have made source code for data generation / training / inference and the model checkpoints publicly available at url123;https://github.com/MARIO&#45;Math&#45;Reasoning/MARIO&#125;. We hope this will facilitate further research and development within the community.
