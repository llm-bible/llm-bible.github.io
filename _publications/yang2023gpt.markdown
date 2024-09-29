---
layout: publication
title: GPT Can Solve Mathematical Problems Without a Calculator
authors: Yang Zhen, Ding Ming, Lv Qingsong, Jiang Zhihuan, He Zehai, Guo Yuyi, Bai Jinfeng, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: yang2023gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03241"}
  - {name: "Code", url: "https://github.com/THUDM/MathGLM"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Previous studies have typically assumed that large language models are unable to accurately perform arithmetic operations particularly multiplication of 8 digits and operations involving decimals and fractions without the use of calculator tools. This paper aims to challenge this misconception. With sufficient training data a 2 billion-parameter language model can accurately perform multi-digit arithmetic operations with almost 100 accuracy without data leakage significantly surpassing GPT-4 (whose multi-digit multiplication accuracy is only 4.3). We also demonstrate that our MathGLM fine-tuned from GLM-10B on a dataset with additional multi-step arithmetic operations and math problems described in text achieves similar performance to GPT-4 on a 5000-samples Chinese math problem test set. Our code and data are public at https://github.com/THUDM/MathGLM.
