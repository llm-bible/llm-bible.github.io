---
layout: publication
title: 'Learning From Students: Applying T-distributions To Explore Accurate And Efficient Formats For Llms'
authors: Dotzel Jordan, Chen Yuzong, Kotb Bahaa, Prasad Sushma, Wu Gang, Li Sheng, Abdelfattah Mohamed S., Zhang Zhiru
conference: "Arxiv"
year: 2024
bibkey: dotzel2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03103"}
  - {name: "Code", url: "https://github.com/cornell-zhang/llm-datatypes"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
'The increasing size of large language models (LLMs) traditionally requires low-precision integer formats to meet strict latency and power demands. Yet recently, alternative formats such as Normal Float (NF4) have increased model accuracy at the cost of increased chip area. In this work, we first conduct a large-scale analysis of LLM weights and activations across 30 networks and conclude that most distributions follow a Student''s t-distribution. We then derive a new theoretically optimal format, Student Float (SF4), that improves over NF4 across modern LLMs, for example increasing the average accuracy on LLaMA2-7B by 0.76&#37; across tasks. Using this format as a high-accuracy reference, we then propose augmenting E2M1 with two variants of supernormal support for higher model accuracy. Finally, we explore the quality and efficiency frontier across 11 datatypes by evaluating their model accuracy and hardware complexity. We discover a Pareto curve composed of INT4, E2M1, and E2M1 with supernormal support, which offers a continuous tradeoff between model accuracy and chip area. For example, E2M1 with supernormal support increases the accuracy of Phi-2 by up to 2.19&#37; with 1.22&#37; area overhead, enabling more LLM-based applications to be run at four bits. The supporting code is hosted at https://github.com/cornell-zhang/llm-datatypes.'
