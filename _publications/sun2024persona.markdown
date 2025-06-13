---
layout: publication
title: 'Persona-db: Efficient Large Language Model Personalization For Response Prediction With Collaborative Data Refinement'
authors: Chenkai Sun, Ke Yang, Revanth Gangi Reddy, Yi R. Fung, Hou Pong Chan, Kevin Small, Chengxiang Zhai, Heng Ji
conference: "Arxiv"
year: 2024
bibkey: sun2024persona
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11060"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
The increasing demand for personalized interactions with large language
models (LLMs) calls for methodologies capable of accurately and efficiently
identifying user opinions and preferences. Retrieval augmentation emerges as an
effective strategy, as it can accommodate a vast number of users without the
costs from fine-tuning. Existing research, however, has largely focused on
enhancing the retrieval stage and devoted limited exploration toward optimizing
the representation of the database, a crucial aspect for tasks such as
personalization. In this work, we examine the problem from a novel angle,
focusing on how data can be better represented for more data-efficient
retrieval in the context of LLM customization. To tackle this challenge, we
introduce Persona-DB, a simple yet effective framework consisting of a
hierarchical construction process to improve generalization across task
contexts and collaborative refinement to effectively bridge knowledge gaps
among users. In the evaluation of response prediction, Persona-DB demonstrates
superior context efficiency in maintaining accuracy with a significantly
reduced retrieval size, a critical advantage in scenarios with extensive
histories or limited context windows. Our experiments also indicate a marked
improvement of over 10% under cold-start scenarios, when users have extremely
sparse data. Furthermore, our analysis reveals the increasing importance of
collaborative knowledge as the retrieval capacity expands.
