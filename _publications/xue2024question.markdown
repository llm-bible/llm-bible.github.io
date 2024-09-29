---
layout: publication
title: Question Calibration And Multi45;hop Modeling For Temporal Question Answering
authors: Xue Chao, Liang Di, Wang Pengfei, Zhang Jing
conference: "Arxiv"
year: 2024
bibkey: xue2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13188"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Many models that leverage knowledge graphs (KGs) have recently demonstrated remarkable success in question answering (QA) tasks. In the real world many facts contained in KGs are time45;constrained thus temporal KGQA has received increasing attention. Despite the fruitful efforts of previous models in temporal KGQA they still have several limitations. (I) They adopt pre45;trained language models (PLMs) to obtain question representations while PLMs tend to focus on entity information and ignore entity transfer caused by temporal constraints and finally fail to learn specific temporal representations of entities. (II) They neither emphasize the graph structure between entities nor explicitly model the multi45;hop relationship in the graph which will make it difficult to solve complex multi45;hop question answering. To alleviate this problem we propose a novel Question Calibration and Multi45;Hop Modeling (QC45;MHM) approach. Specifically We first calibrate the question representation by fusing the question and the time45;constrained concepts in KG. Then we construct the GNN layer to complete multi45;hop message passing. Finally the question representation is combined with the embedding output by the GNN to generate the final prediction. Empirical results verify that the proposed model achieves better performance than the state45;of45;the45;art models in the benchmark dataset. Notably the Hits35;64;1 and Hits35;64;10 results of QC45;MHM on the CronQuestions datasets complex questions are absolutely improved by 5.137; and 1.237; compared to the best45;performing baseline. Moreover QC45;MHM can generate interpretable and trustworthy predictions.
