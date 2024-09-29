---
layout: publication
title: LoRec Large Language Model for Robust Sequential Recommendation against Poisoning Attacks
authors: Zhang Kaike, Cao Qi, Wu Yunfan, Sun Fei, Shen Huawei, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: zhang2024lorec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17723"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Sequential recommender systems stand out for their ability to capture users dynamic interests and the patterns of item-to-item transitions. However the inherent openness of sequential recommender systems renders them vulnerable to poisoning attacks where fraudulent users are injected into the training data to manipulate learned patterns. Traditional defense strategies predominantly depend on predefined assumptions or rules extracted from specific known attacks limiting their generalizability to unknown attack types. To solve the above problems considering the rich open-world knowledge encapsulated in Large Language Models (LLMs) our research initially focuses on the capabilities of LLMs in the detection of unknown fraudulent activities within recommender systems a strategy we denote as LLM4Dec. Empirical evaluations demonstrate the substantial capability of LLMs in identifying unknown fraudsters leveraging their expansive open-world knowledge. Building upon this we propose the integration of LLMs into defense strategies to extend their effectiveness beyond the confines of known attacks. We propose LoRec an advanced framework that employs LLM-Enhanced Calibration to strengthen the robustness of sequential recommender systems against poisoning attacks. LoRec integrates an LLM-enhanced CalibraTor (LCT) that refines the training process of sequential recommender systems with knowledge derived from LLMs applying a user-wise reweighting to diminish the impact of fraudsters injected by attacks. By incorporating LLMs open-world knowledge the LCT effectively converts the limited specific priors or rules into a more general pattern of fraudsters offering improved defenses against poisoning attacks. Our comprehensive experiments validate that LoRec as a general framework significantly strengthens the robustness of sequential recommender systems.
