---
layout: publication
title: Sesamebert Attention For Anywhere
authors: Su Ta-chun, Cheng Hsiang-chih
conference: "Arxiv"
year: 2019
bibkey: su2019attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.03176"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Reinforcement Learning']
---
Fine45;tuning with pre45;trained models has achieved exceptional results for many language tasks. In this study we focused on one such self45;attention network model namely BERT which has performed well in terms of stacking layers across diverse language45;understanding benchmarks. However in many downstream tasks information between layers is ignored by BERT for fine45;tuning. In addition although self45;attention networks are well45;known for their ability to capture global dependencies room for improvement remains in terms of emphasizing the importance of local contexts. In light of these advantages and disadvantages this paper proposes SesameBERT a generalized fine45;tuning method that (1) enables the extraction of global information among all layers through Squeeze and Excitation and (2) enriches local information by capturing neighboring contexts via Gaussian blurring. Furthermore we demonstrated the effectiveness of our approach in the HANS dataset which is used to determine whether models have adopted shallow heuristics instead of learning underlying generalizations. The experiments revealed that SesameBERT outperformed BERT with respect to GLUE benchmark and the HANS evaluation set.
