---
layout: publication
title: Goal45;guided Generative Prompt Injection Attack On Large Language Models
authors: Zhang Chong, Jin Mingyu, Yu Qinkai, Liu Chengzhi, Xue Haochen, Jin Xiaobo
conference: "Arxiv"
year: 2024
bibkey: zhang2024goal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07234"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security']
---
Current large language models (LLMs) provide a strong foundation for large45;scale user45;oriented natural language tasks. A large number of users can easily inject adversarial text or instructions through the user interface thus causing LLMs model security challenges. Although there is currently a large amount of research on prompt injection attacks most of these black45;box attacks use heuristic strategies. It is unclear how these heuristic strategies relate to the success rate of attacks and thus effectively improve model robustness. To solve this problem we redefine the goal of the attack to maximize the KL divergence between the conditional probabilities of the clean text and the adversarial text. Furthermore we prove that maximizing the KL divergence is equivalent to maximizing the Mahalanobis distance between the embedded representation x and x of the clean text and the adversarial text when the conditional probability is a Gaussian distribution and gives a quantitative relationship on x and x. Then we designed a simple and effective goal45;guided generative prompt injection strategy (G2PIA) to find an injection text that satisfies specific constraints to achieve the optimal attack effect approximately. It is particularly noteworthy that our attack method is a query45;free black45;box attack method with low computational cost. Experimental results on seven LLM models and four datasets show the effectiveness of our attack method.
