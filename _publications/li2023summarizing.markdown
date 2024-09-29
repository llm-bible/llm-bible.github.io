---
layout: publication
title: Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation
authors: Li Miao, Hovy Eduard, Lau Jey Han
conference: "Arxiv"
year: 2023
bibkey: li2023summarizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.01498"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Survey Paper', 'Training Techniques']
---
We present PeerSum a novel dataset for generating meta-reviews of scientific papers. The meta-reviews can be interpreted as abstractive summaries of reviews multi-turn discussions and the paper abstract. These source documents have rich inter-document relationships with an explicit hierarchical conversational structure cross-references and (occasionally) conflicting information. To introduce the structural inductive bias into pre-trained language models we introduce Rammer ( Relationship-aware Multi-task Meta-review Generator) a model that uses sparse attention based on the conversational structure and a multi-task training objective that predicts metadata features (e.g. review ratings). Our experimental results show that Rammer outperforms other strong baseline models in terms of a suite of automatic evaluation metrics. Further analyses however reveal that RAMMER and other models struggle to handle conflicts in source documents of PeerSum suggesting meta-review generation is a challenging task and a promising avenue for further research.
