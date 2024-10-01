---
layout: publication
title: 'Convsdg: Session Data Generation For Conversational Search'
authors: Mo Fengran, Yi Bole, Mao Kelong, Qu Chen, Huang Kaiyu, Nie Jian-yun
conference: "Arxiv"
year: 2024
bibkey: mo2024session
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11335"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Conversational search provides a more convenient interface for users to search by allowing multi-turn interaction with the search engine. However, the effectiveness of the conversational dense retrieval methods is limited by the scarcity of training data required for their fine-tuning. Thus, generating more training conversational sessions with relevant labels could potentially improve search performance. Based on the promising capabilities of large language models (LLMs) on text generation, we propose ConvSDG, a simple yet effective framework to explore the feasibility of boosting conversational search by using LLM for session data generation. Within this framework, we design dialogue/session-level and query-level data generation with unsupervised and semi-supervised learning, according to the availability of relevance judgments. The generated data are used to fine-tune the conversational dense retriever. Extensive experiments on four widely used datasets demonstrate the effectiveness and broad applicability of our ConvSDG framework compared with several strong baselines.
