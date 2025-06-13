---
layout: publication
title: 'Making Them Ask And Answer: Jailbreaking Large Language Models In Few Queries Via Disguise And Reconstruction'
authors: Tong Liu, Yingjie Zhang, Zhe Zhao, Yinpeng Dong, Guozhu Meng, Kai Chen
conference: "Arxiv"
year: 2024
bibkey: liu2024making
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.18104'}
tags: ['Efficiency and Optimization', 'Security', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Ethics and Bias', 'Responsible AI', 'Pretraining Methods']
---
In recent years, large language models (LLMs) have demonstrated notable
success across various tasks, but the trustworthiness of LLMs is still an open
problem. One specific threat is the potential to generate toxic or harmful
responses. Attackers can craft adversarial prompts that induce harmful
responses from LLMs. In this work, we pioneer a theoretical foundation in LLMs
security by identifying bias vulnerabilities within the safety fine-tuning and
design a black-box jailbreak method named DRA (Disguise and Reconstruction
Attack), which conceals harmful instructions through disguise and prompts the
model to reconstruct the original harmful instruction within its completion. We
evaluate DRA across various open-source and closed-source models, showcasing
state-of-the-art jailbreak success rates and attack efficiency. Notably, DRA
boasts a 91.1% attack success rate on OpenAI GPT-4 chatbot.
