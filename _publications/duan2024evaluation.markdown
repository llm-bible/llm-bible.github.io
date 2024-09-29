---
layout: publication
title: On the Evaluation Consistency of Attribution-based Explanations
authors: Duan Jiarui, Li Haoling, Zhang Haofei, Jiang Hao, Xue Mengqi, Sun Li, Song Mingli, Song Jie
conference: "Arxiv"
year: 2024
bibkey: duan2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19471"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Attribution-based explanations are garnering increasing attention recently and have emerged as the predominant approach towards ~(XAI). However the absence of consistent configurations and systematic investigations in prior literature impedes comprehensive evaluations of existing methodologies. In this work we introduce Meta-Rank an open platform for benchmarking attribution methods in the image domain. Presently Meta-Rank assesses eight exemplary attribution methods using six renowned model architectures on four diverse datasets employing both the (MoRF) and (LeRF) evaluation protocols. Through extensive experimentation our benchmark reveals three insights in attribution evaluation endeavors 1) evaluating attribution methods under disparate settings can yield divergent performance rankings; 2) although inconsistent across numerous cases the performance rankings exhibit remarkable consistency across distinct checkpoints along the same training trajectory; 3) prior attempts at consistent evaluation fare no better than baselines when extended to more heterogeneous models and datasets. Our findings underscore the necessity for future research in this domain to conduct rigorous evaluations encompassing a broader range of models and datasets and to reassess the assumptions underlying the empirical success of different attribution methods. Our code is publicly available at .
