---
layout: publication
title: Strengthened Symbol Binding Makes Large Language Models Reliable Multiple-choice Selectors
authors: Xue Mengge, Hu Zhenyu, Liu Liqun, Liao Kuo, Li Shuang, Han Honglin, Zhao Meng, Yin Chengguo
conference: "ACL"
year: 2024
bibkey: xue2024strengthened
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01026"}
tags: ['Ethics And Bias', 'Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Multiple-Choice Questions (MCQs) constitute a critical area of research in the study of Large Language Models (LLMs). Previous works have investigated the selection bias problem in MCQs within few-shot scenarios in which the LLMs performance may be influenced by the presentation of answer choices leaving the selection bias during Supervised Fine-Tuning (SFT) unexplored. In this paper we reveal that selection bias persists in the SFT phase primarily due to the LLMs inadequate Multiple Choice Symbol Binding (MCSB) ability. This limitation implies that the model struggles to associate the answer options with their corresponding symbols (e.g. A/B/C/D) effectively. To enhance the models MCSB capability we first incorporate option contents into the loss function and subsequently adjust the weights of the option symbols and contents guiding the model to understand the option content of the current symbol. Based on this we introduce an efficient SFT algorithm for MCQs termed Point-wise Intelligent Feedback (PIF). PIF constructs negative instances by randomly combining the incorrect option contents with all candidate symbols and proposes a point-wise loss to provide feedback on these negative samples into LLMs. Our experimental results demonstrate that PIF significantly reduces the models selection bias by improving its MCSB capability. Remarkably PIF exhibits a substantial enhancement in the accuracy for MCQs.
