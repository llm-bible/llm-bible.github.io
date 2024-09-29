---
layout: publication
title: Inpars45;light Cost45;effective Unsupervised Training Of Efficient Rankers
authors: Boytsov Leonid, Patel Preksha, Sourabh Vivek, Nisar Riddhi, Kundu Sayani, Ramanathan Ramya, Nyberg Eric
conference: "Arxiv"
year: 2023
bibkey: boytsov2023inpars
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.02998"}
  - {name: "Code", url: "https://github.com/searchivarius/inpars&#95;light/"}
tags: ['BERT', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
We carried out a reproducibility study of InPars which is a method for unsupervised training of neural rankers (Bonifacio et al. 2022). As a by45;product we developed InPars45;light which is a simple45;yet45;effective modification of InPars. Unlike InPars InPars45;light uses 7x45;100x smaller ranking models and only a freely available language model BLOOM which 45;45; as we found out 45;45; produced more accurate rankers compared to a proprietary GPT45;3 model. On all five English retrieval collections (used in the original InPars study) we obtained substantial (737;45;3037;) and statistically significant improvements over BM25 (in nDCG and MRR) using only a 30M parameter six45;layer MiniLM45;30M ranker and a single three45;shot prompt. In contrast in the InPars study only a 100x larger monoT545;3B model consistently outperformed BM25 whereas their smaller monoT545;220M model (which is still 7x larger than our MiniLM ranker) outperformed BM25 only on MS MARCO and TREC DL 2020. In the same three45;shot prompting scenario our 435M parameter DeBERTA v3 ranker was at par with the 7x larger monoT545;3B (average gain over BM25 of 1.3 vs 1.32) In fact on three out of five datasets DeBERTA slightly outperformed monoT545;3B. Finally these good results were achieved by re45;ranking only 100 candidate documents compared to 1000 used by Bonifacio et al. (2022). We believe that InPars45;light is the first truly cost45;effective prompt45;based unsupervised recipe to train and deploy neural ranking models that outperform BM25. Our code and data is publicly available. https://github.com/searchivarius/inpars&#95;light/
