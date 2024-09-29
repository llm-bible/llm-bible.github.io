---
layout: publication
title: Unleashing The Power Of Pre45;trained Language Models For Offline Reinforcement Learning
authors: Shi Ruizhe, Liu Yuyao, Ze Yanjie, Du Simon S., Xu Huazhe
conference: "Arxiv"
year: 2023
bibkey: shi2023unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20587"}
tags: ['Agentic', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Offline reinforcement learning (RL) aims to find a near45;optimal policy using pre45;collected datasets. In real45;world scenarios data collection could be costly and risky; therefore offline RL becomes particularly challenging when the in45;domain data is limited. Given recent advances in Large Language Models (LLMs) and their few45;shot learning prowess this paper introduces textbf123;La125;nguage Models for textbf123;Mo125;tion Control (textbf123;LaMo125;) a general framework based on Decision Transformers to effectively use pre45;trained Language Models (LMs) for offline RL. Our framework highlights four crucial components (1) Initializing Decision Transformers with sequentially pre45;trained LMs (2) employing the LoRA fine45;tuning method in contrast to full45;weight fine45;tuning to combine the pre45;trained knowledge from LMs and in45;domain knowledge effectively (3) using the non45;linear MLP transformation instead of linear projections to generate embeddings and (4) integrating an auxiliary language prediction loss during fine45;tuning to stabilize the LMs and retain their original abilities on languages. Empirical results indicate textbf123;LaMo125; achieves state45;of45;the45;art performance in sparse45;reward tasks and closes the gap between value45;based offline RL methods and decision transformers in dense45;reward tasks. In particular our method demonstrates superior performance in scenarios with limited data samples.
