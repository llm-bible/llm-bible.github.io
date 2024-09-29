---
layout: publication
title: The Janus Interface How Fine45;tuning In Large Language Models Amplifies The Privacy Risks
authors: Chen Xiaoyi, Tang Siyuan, Zhu Rui, Yan Shijun, Jin Lei, Wang Zihao, Su Liya, Zhang Zhikun, Wang Xiaofeng, Tang Haixu
conference: "ACM CCS"
year: 2023
bibkey: chen2023janus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15469"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Security', 'Tools', 'Training Techniques']
---
The rapid advancements of large language models (LLMs) have raised public concerns about the privacy leakage of personally identifiable information (PII) within their extensive training datasets. Recent studies have demonstrated that an adversary could extract highly sensitive privacy data from the training data of LLMs with carefully designed prompts. However these attacks suffer from the models tendency to hallucinate and catastrophic forgetting (CF) in the pre45;training stage rendering the veracity of divulged PIIs negligible. In our research we propose a novel attack Janus which exploits the fine45;tuning interface to recover forgotten PIIs from the pre45;training data in LLMs. We formalize the privacy leakage problem in LLMs and explain why forgotten PIIs can be recovered through empirical analysis on open45;source language models. Based upon these insights we evaluate the performance of Janus on both open45;source language models and two latest LLMs i.e. GPT45;3.545;Turbo and LLaMA45;245;7b. Our experiment results show that Janus amplifies the privacy risks by over 10 times in comparison with the baseline and significantly outperforms the state45;of45;the45;art privacy extraction attacks including prefix attacks and in45;context learning (ICL). Furthermore our analysis validates that existing fine45;tuning APIs provided by OpenAI and Azure AI Studio are susceptible to our Janus attack allowing an adversary to conduct such an attack at a low cost.
