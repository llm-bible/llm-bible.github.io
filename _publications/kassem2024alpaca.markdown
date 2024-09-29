---
layout: publication
title: Alpaca Against Vicuna Using Llms To Uncover Memorization Of Llms
authors: Kassem Aly M., Mahmoud Omar, Mireshghallah Niloofar, Kim Hyunwoo, Tsvetkov Yulia, Choi Yejin, Saad Sherif, Rana Santu
conference: "Arxiv"
year: 2024
bibkey: kassem2024alpaca
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04801"}
  - {name: "Code", url: "https://github.com/Alymostafa/Instruction&#95;based&#95;attack"}
tags: ['Agentic', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
In this paper we introduce a black45;box prompt optimization method that uses an attacker LLM agent to uncover higher levels of memorization in a victim agent compared to what is revealed by prompting the target model with the training data directly which is the dominant approach of quantifying memorization in LLMs. We use an iterative rejection45;sampling optimization process to find instruction45;based prompts with two main characteristics (1) minimal overlap with the training data to avoid presenting the solution directly to the model and (2) maximal overlap between the victim models output and the training data aiming to induce the victim to spit out training data. We observe that our instruction45;based prompts generate outputs with 23.737; higher overlap with training data compared to the baseline prefix45;suffix measurements. Our findings show that (1) instruction45;tuned models can expose pre45;training data as much as their base45;models if not more so (2) contexts other than the original training data can lead to leakage and (3) using instructions proposed by other LLMs can open a new avenue of automated attacks that we should further study and explore. The code can be found at https://github.com/Alymostafa/Instruction&#95;based&#95;attack .
