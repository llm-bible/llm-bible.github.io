---
layout: publication
title: Can LLM Be A Personalized Judge
authors: Dong Yijiang River, Hu Tiancheng, Collier Nigel
conference: "Arxiv"
year: 2024
bibkey: dong2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11657"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Ensuring that large language models (LLMs) reflect diverse user values and preferences is crucial as their user bases expand globally. It is therefore encouraging to see the growing interest in LLM personalization within the research community. However current works often rely on the LLM45;as45;a45;Judge approach for evaluation without thoroughly examining its validity. In this paper we investigate the reliability of LLM45;as45;a45;Personalized45;Judge asking LLMs to judge user preferences based on personas. Our findings suggest that directly applying LLM45;as45;a45;Personalized45;Judge is less reliable than previously assumed showing low and inconsistent agreement with human ground truth. The personas typically used are often overly simplistic resulting in low predictive power. To address these issues we introduce verbal uncertainty estimation into the LLM45;as45;a45;Personalized45;Judge pipeline allowing the model to express low confidence on uncertain judgments. This adjustment leads to much higher agreement (above 8037;) on high45;certainty samples for binary tasks. Through human evaluation we find that the LLM45;as45;a45;Personalized45;Judge achieves comparable performance to third45;party humans evaluation and even surpasses human performance on high45;certainty samples. Our work indicates that certainty45;enhanced LLM45;as45;a45;Personalized45;Judge offers a promising direction for developing more reliable and scalable methods for evaluating LLM personalization.
