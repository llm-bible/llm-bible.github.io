---
layout: publication
title: 'Faithful Persona-based Conversational Dataset Generation With Large Language Models'
authors: Jandaghi Pegah, Sheng Xianghai, Bai Xinyi, Pujara Jay, Sidahmed Hakim
conference: "Arxiv"
year: 2023
bibkey: jandaghi2023faithful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10007"}
tags: ['Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
'High-quality conversational datasets are essential for developing AI models that can communicate with users. One way to foster deeper interactions between a chatbot and its user is through personas, aspects of the user''s character that provide insights into their personality, motivations, and behaviors. Training Natural Language Processing (NLP) models on a diverse and comprehensive persona-based dataset can lead to conversational models that create a deeper connection with the user, and maintain their engagement. In this paper, we leverage the power of Large Language Models (LLMs) to create a large, high-quality conversational dataset from a seed dataset. We propose a Generator-Critic architecture framework to expand the initial dataset, while improving the quality of its conversations. The Generator is an LLM prompted to output conversations. The Critic consists of a mixture of expert LLMs that control the quality of the generated conversations. These experts select the best generated conversations, which we then use to improve the Generator. We release Synthetic-Persona-Chat, consisting of 20k conversations seeded from Persona-Chat. We evaluate the quality of Synthetic-Persona-Chat and our generation framework on different dimensions through extensive experiments, and observe that the losing rate of Synthetic-Persona-Chat against Persona-Chat during Turing test decreases from 17.2&#37; to 8.8&#37; over three iterations.'
