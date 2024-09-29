---
layout: publication
title: What are the limits of cross-lingual dense passage retrieval for low-resource languages
authors: Wu Jie, Ren Zhaochun, Verberne Suzan
conference: "Arxiv"
year: 2024
bibkey: wu2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11942"}
  - {name: "Code", url: "https://anonymous.4open.science/r/Question-Answering-for-Low-Resource-Languages-B13C/"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
In this paper we analyze the capabilities of the multi-lingual Dense Passage Retriever (mDPR) for extremely low-resource languages. In the Cross-lingual Open-Retrieval Answer Generation (CORA) pipeline mDPR achieves success on multilingual open QA benchmarks across 26 languages of which 9 were unseen during training. These results are promising for Question Answering (QA) for low-resource languages. We focus on two extremely low-resource languages for which mDPR performs poorly Amharic and Khmer. We collect and curate datasets to train mDPR models using Translation Language Modeling (TLM) and question--passage alignment. We also investigate the effect of our extension on the language distribution in the retrieval results. Our results on the MKQA and AmQA datasets show that language alignment brings improvements to mDPR for the low-resource languages but the improvements are modest and the results remain low. We conclude that fulfilling CORAs promise to enable multilingual open QA in extremely low-resource settings is challenging because the model the data and the evaluation approach are intertwined. Hence all three need attention in follow-up work. We release our code for reproducibility and future work https://anonymous.4open.science/r/Question-Answering-for-Low-Resource-Languages-B13C/
