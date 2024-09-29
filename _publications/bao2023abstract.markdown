---
layout: publication
title: Abstract Meaning Representation-based Logic-driven Data Augmentation For Logical Reasoning
authors: Bao Qiming, Peng Alex Yuxuan, Deng Zhenyun, Zhong Wanjun, Gendron Gael, Pistotti Timothy, Tan Neset, Young Nathan, Chen Yang, Zhu Yonghua, Denny Paul, Witbrock Michael, Liu Jiamou
conference: "Arxiv"
year: 2023
bibkey: bao2023abstract
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12599"}
  - {name: "Code", url: "https://eval.ai/web/challenges/challenge-page/503/leaderboard/1347"}
  - {name: "Code", url: "https://github.com/Strong-AI-Lab/Logical-Equivalence-driven-AMR-Data-Augmentation-for-Representation-Learning"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Combining large language models with logical reasoning enhances their capacity to address problems in a robust and reliable manner. Nevertheless the intricate nature of logical reasoning poses challenges when gathering reliable data from the web to build comprehensive training datasets subsequently affecting performance on downstream tasks. To address this we introduce a novel logic-driven data augmentation approach AMR-LDA. AMR-LDA converts the original text into an Abstract Meaning Representation (AMR) graph a structured semantic representation that encapsulates the logical structure of the sentence upon which operations are performed to generate logically modified AMR graphs. The modified AMR graphs are subsequently converted back into text to create augmented data. Notably our methodology is architecture-agnostic and enhances both generative large language models such as GPT-3.5 and GPT-4 through prompt augmentation and discriminative large language models through contrastive learning with logic-driven data augmentation. Empirical evidence underscores the efficacy of our proposed method with improvement in performance across seven downstream tasks such as reading comprehension requiring logical reasoning textual entailment and natural language inference. Furthermore our method leads on the ReClor leaderboard at https://eval.ai/web/challenges/challenge-page/503/leaderboard/1347. The source code and data are publicly available at https://github.com/Strong-AI-Lab/Logical-Equivalence-driven-AMR-Data-Augmentation-for-Representation-Learning."
