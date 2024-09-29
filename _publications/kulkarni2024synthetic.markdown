---
layout: publication
title: Synthdst Synthetic Data Is All You Need For Few45;shot Dialog State Tracking
authors: Kulkarni Atharva, Tseng Bo-hsiang, Moniz Joel Ruben Antony, Piraviperumal Dhivya, Yu Hong, Bhargava Shruti
conference: "Arxiv"
year: 2024
bibkey: kulkarni2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02285"}
  - {name: "Code", url: "https://github.com/apple/ml&#45;synthdst"}
tags: ['Applications', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In45;context learning with Large Language Models (LLMs) has emerged as a promising avenue of research in Dialog State Tracking (DST). However the best45;performing in45;context learning methods involve retrieving and adding similar examples to the prompt requiring access to labeled training data. Procuring such training data for a wide range of domains and applications is time45;consuming expensive and at times infeasible. While zero45;shot learning requires no training data it significantly lags behind the few45;shot setup. Thus textit123;Can we efficiently generate synthetic data for any dialogue schema to enable few45;shot prompting125; Addressing this question we propose method a data generation framework tailored for DST utilizing LLMs. Our approach only requires the dialogue schema and a few hand45;crafted dialogue templates to synthesize natural coherent and free45;flowing dialogues with DST annotations. Few45;shot learning using data from 123;method125; results in 445;537; improvement in Joint Goal Accuracy over the zero45;shot baseline on MultiWOZ 2.1 and 2.4. Remarkably our few45;shot learning approach recovers nearly 9837; of the performance compared to the few45;shot setup using human45;annotated training data. Our synthetic data and code can be accessed at https://github.com/apple/ml&#45;synthdst
