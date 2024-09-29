---
layout: publication
title: Soft Prompt Decoding For Multilingual Dense Retrieval
authors: Huang Zhiqi, Zeng Hansi, Zamani Hamed, Allan James
conference: "Arxiv"
year: 2023
bibkey: huang2023soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09025"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
In this work we explore a Multilingual Information Retrieval (MLIR) task where the collection includes documents in multiple languages. We demonstrate that applying state45;of45;the45;art approaches developed for cross45;lingual information retrieval to MLIR tasks leads to sub45;optimal performance. This is due to the heterogeneous and imbalanced nature of multilingual collections 45;45; some languages are better represented in the collection and some benefit from large45;scale training data. To address this issue we present KD45;SPD a novel soft prompt decoding approach for MLIR that implicitly translates the representation of documents in different languages into the same embedding space. To address the challenges of data scarcity and imbalance we introduce a knowledge distillation strategy. The teacher model is trained on rich English retrieval data and by leveraging bi45;text data our distillation framework transfers its retrieval knowledge to the multilingual document encoder. Therefore our approach does not require any multilingual retrieval training data. Extensive experiments on three MLIR datasets with a total of 15 languages demonstrate that KD45;SPD significantly outperforms competitive baselines in all cases. We conduct extensive analyses to show that our method has less language bias and better zero45;shot transfer ability towards new languages.
