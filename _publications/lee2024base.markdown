---
layout: publication
title: 'BAPO: Base-anchored Preference Optimization For Overcoming Forgetting In Large Language Models Personalization'
authors: Gihun Lee, Minchan Jeong, Yujin Kim, Hojung Jung, Jaehoon Oh, Sangmook Kim, Se-young Yun
conference: "Arxiv"
year: 2024
bibkey: lee2024base
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00693"}
tags: ['Efficiency and Optimization']
---
While learning to align Large Language Models (LLMs) with human preferences
has shown remarkable success, aligning these models to meet the diverse user
preferences presents further challenges in preserving previous knowledge. This
paper examines the impact of personalized preference optimization on LLMs,
revealing that the extent of knowledge loss varies significantly with
preference heterogeneity. Although previous approaches have utilized the KL
constraint between the reference model and the policy model, we observe that
they fail to maintain general knowledge and alignment when facing personalized
preferences. To this end, we introduce Base-Anchored Preference Optimization
(BAPO), a simple yet effective approach that utilizes the initial responses of
reference model to mitigate forgetting while accommodating personalized
alignment. BAPO effectively adapts to diverse user preferences while minimally
affecting global knowledge or general alignment. Our experiments demonstrate
the efficacy of BAPO in various setups.
