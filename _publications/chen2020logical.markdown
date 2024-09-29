---
layout: publication
title: Logical Natural Language Generation From Open45;domain Tables
authors: Chen Wenhu, Chen Jianshu, Su Yu, Chen Zhiyu, Wang William Yang
conference: "Arxiv"
year: 2020
bibkey: chen2020logical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.10404"}
  - {name: "Code", url: "https://github.com/wenhuchen/LogicNLG&#125;"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Survey Paper', 'Tools', 'Training Techniques', 'Transformer']
---
Neural natural language generation (NLG) models have recently shown remarkable progress in fluency and coherence. However existing studies on neural NLG are primarily focused on surface45;level realizations with limited emphasis on logical inference an important aspect of human thinking and language. In this paper we suggest a new NLG task where a model is tasked with generating natural language statements that can be emph123;logically entailed125; by the facts in an open45;domain semi45;structured table. To facilitate the study of the proposed logical NLG problem we use the existing TabFact dataset cite123;chen2019tabfact125; featured with a wide range of logical/symbolic inferences as our testbed and propose new automatic metrics to evaluate the fidelity of generation models w.r.t. logical inference. The new task poses challenges to the existing monotonic generation frameworks due to the mismatch between sequence order and logical order. In our experiments we comprehensively survey different generation architectures (LSTM Transformer Pre45;Trained LM) trained with different algorithms (RL Adversarial Training Coarse45;to45;Fine) on the dataset and made following observations 1) Pre45;Trained LM can significantly boost both the fluency and logical fidelity metrics 2) RL and Adversarial Training are trading fluency for fidelity 3) Coarse45;to45;Fine generation can help partially alleviate the fidelity issue while maintaining high language fluency. The code and data are available at url123;https://github.com/wenhuchen/LogicNLG&#125;.
