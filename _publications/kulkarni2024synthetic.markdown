---
layout: publication
title: Synthdst Synthetic Data Is All You Need For Few-shot Dialog State Tracking
authors: Kulkarni Atharva, Tseng Bo-hsiang, Moniz Joel Ruben Antony, Piraviperumal Dhivya, Yu Hong, Bhargava Shruti
conference: "Arxiv"
year: 2024
bibkey: kulkarni2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02285"}
  - {name: "Code", url: "https://github.com/apple/ml-synthdst"}
tags: ['Applications', 'Few Shot', 'Has Code', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In-context learning with Large Language Models (LLMs) has emerged as a promising avenue of research in Dialog State Tracking (DST). However the best-performing in-context learning methods involve retrieving and adding similar examples to the prompt requiring access to labeled training data. Procuring such training data for a wide range of domains and applications is time-consuming expensive and at times infeasible. While zero-shot learning requires no training data it significantly lags behind the few-shot setup. Thus (textit)Can we efficiently generate synthetic data for any dialogue schema to enable few-shot prompting Addressing this question we propose (method) a data generation framework tailored for DST utilizing LLMs. Our approach only requires the dialogue schema and a few hand-crafted dialogue templates to synthesize natural coherent and free-flowing dialogues with DST annotations. Few-shot learning using data from (method) results in 4-537; improvement in Joint Goal Accuracy over the zero-shot baseline on MultiWOZ 2.1 and 2.4. Remarkably our few-shot learning approach recovers nearly 9837; of the performance compared to the few-shot setup using human-annotated training data. Our synthetic data and code can be accessed at https://github.com/apple/ml-synthdst"
