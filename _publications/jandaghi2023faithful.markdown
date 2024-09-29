---
layout: publication
title: Faithful Persona45;based Conversational Dataset Generation With Large Language Models
authors: Jandaghi Pegah, Sheng Xianghai, Bai Xinyi, Pujara Jay, Sidahmed Hakim
conference: "Arxiv"
year: 2023
bibkey: jandaghi2023faithful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10007"}
tags: ['Applications', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
High45;quality conversational datasets are essential for developing AI models that can communicate with users. One way to foster deeper interactions between a chatbot and its user is through personas aspects of the users character that provide insights into their personality motivations and behaviors. Training Natural Language Processing (NLP) models on a diverse and comprehensive persona45;based dataset can lead to conversational models that create a deeper connection with the user and maintain their engagement. In this paper we leverage the power of Large Language Models (LLMs) to create a large high45;quality conversational dataset from a seed dataset. We propose a Generator45;Critic architecture framework to expand the initial dataset while improving the quality of its conversations. The Generator is an LLM prompted to output conversations. The Critic consists of a mixture of expert LLMs that control the quality of the generated conversations. These experts select the best generated conversations which we then use to improve the Generator. We release Synthetic45;Persona45;Chat consisting of 20k conversations seeded from Persona45;Chat. We evaluate the quality of Synthetic45;Persona45;Chat and our generation framework on different dimensions through extensive experiments and observe that the losing rate of Synthetic45;Persona45;Chat against Persona45;Chat during Turing test decreases from 17.237; to 8.837; over three iterations.
