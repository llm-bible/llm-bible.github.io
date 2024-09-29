---
layout: publication
title: Unintended Bias In Language Model45;driven Conversational Recommendation
authors: Shen Tianshu, Li Jiaru, Bouadjenek Mohamed Reda, Mai Zheda, Sanner Scott
conference: "Arxiv"
year: 2022
bibkey: shen2022unintended
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.06224"}
tags: ['BERT', 'Ethics And Bias', 'Model Architecture', 'RAG', 'Training Techniques']
---
Conversational Recommendation Systems (CRSs) have recently started to leverage pretrained language models (LM) such as BERT for their ability to semantically interpret a wide range of preference statement variations. However pretrained LMs are well45;known to be prone to intrinsic biases in their training data which may be exacerbated by biases embedded in domain45;specific language data(e.g. user reviews) used to fine45;tune LMs for CRSs. We study a recently introduced LM45;driven recommendation backbone (termed LMRec) of a CRS to investigate how unintended bias i.e. language variations such as name references or indirect indicators of sexual orientation or location that should not affect recommendations manifests in significantly shifted price and category distributions of restaurant recommendations. The alarming results we observe strongly indicate that LMRec has learned to reinforce harmful stereotypes through its recommendations. For example offhand mention of names associated with the black community significantly lowers the price distribution of recommended restaurants while offhand mentions of common male45;associated names lead to an increase in recommended alcohol45;serving establishments. These and many related results presented in this work raise a red flag that advances in the language handling capability of LM45;drivenCRSs do not come without significant challenges related to mitigating unintended bias in future deployed CRS assistants with a potential reach of hundreds of millions of end45;users.
