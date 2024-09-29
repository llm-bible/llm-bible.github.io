---
layout: publication
title: Training Language Models To Generate Text With Citations Via Fine45;grained Rewards
authors: Huang Chengyu, Wu Zeqiu, Hu Yushi, Wang Wenya
conference: "Arxiv"
year: 2024
bibkey: huang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04315"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While recent Large Language Models (LLMs) have proven useful in answering user queries they are prone to hallucination and their responses often lack credibility due to missing references to reliable sources. An intuitive solution to these issues would be to include in45;text citations referring to external documents as evidence. While previous works have directly prompted LLMs to generate in45;text citations their performances are far from satisfactory especially when it comes to smaller LLMs. In this work we propose an effective training framework using fine45;grained rewards to teach LLMs to generate highly supportive and relevant citations while ensuring the correctness of their responses. We also conduct a systematic analysis of applying these fine45;grained rewards to common LLM training strategies demonstrating its advantage over conventional practices. We conduct extensive experiments on Question Answering (QA) datasets taken from the ALCE benchmark and validate the models generalizability using EXPERTQA. On LLaMA45;245;7B the incorporation of fine45;grained rewards achieves the best performance among the baselines even surpassing that of GPT45;3.545;turbo.
