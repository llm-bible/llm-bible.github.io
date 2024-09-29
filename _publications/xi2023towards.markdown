---
layout: publication
title: Towards Open45;world Recommendation With Knowledge Augmentation From Large Language Models
authors: Xi Yunjia, Liu Weiwen, Lin Jianghao, Cai Xiaoling, Zhu Hong, Zhu Jieming, Chen Bo, Tang Ruiming, Zhang Weinan, Zhang Rui, Yu Yong
conference: "Arxiv"
year: 2023
bibkey: xi2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.10933"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recommender systems play a vital role in various online services. However the insulated nature of training and deploying separately within a specific domain limits their access to open45;world knowledge. Recently the emergence of large language models (LLMs) has shown promise in bridging this gap by encoding extensive world knowledge and demonstrating reasoning capability. Nevertheless previous attempts to directly use LLMs as recommenders have not achieved satisfactory results. In this work we propose an Open45;World Knowledge Augmented Recommendation Framework with Large Language Models dubbed KAR to acquire two types of external knowledge from LLMs 45;45; the reasoning knowledge on user preferences and the factual knowledge on items. We introduce factorization prompting to elicit accurate reasoning on user preferences. The generated reasoning and factual knowledge are effectively transformed and condensed into augmented vectors by a hybrid45;expert adaptor in order to be compatible with the recommendation task. The obtained vectors can then be directly used to enhance the performance of any recommendation model. We also ensure efficient inference by preprocessing and prestoring the knowledge from the LLM. Extensive experiments show that KAR significantly outperforms the state45;of45;the45;art baselines and is compatible with a wide range of recommendation algorithms. We deploy KAR to Huaweis news and music recommendation platforms and gain a 737; and 1.737; improvement in the online A/B test respectively.
