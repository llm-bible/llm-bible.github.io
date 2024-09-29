---
layout: publication
title: Generative Or Contrastive Phrase Reconstruction For Better Sentence Representation Learning
authors: Wu Bohong, Zhao Hai
conference: "Arxiv"
year: 2022
bibkey: wu2022generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.09358"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Though offering amazing contextualized token45;level representations current pre45;trained language models actually take less attention on acquiring sentence45;level representation during its self45;supervised pre45;training. If self45;supervised learning can be distinguished into two subcategories generative and contrastive then most existing studies show that sentence representation learning may more benefit from the contrastive methods but not the generative methods. However contrastive learning cannot be well compatible with the common token45;level generative self45;supervised learning and does not guarantee good performance on downstream semantic retrieval tasks. Thus to alleviate such obvious inconveniences we instead propose a novel generative self45;supervised learning objective based on phrase reconstruction. Empirical studies show that our generative learning may yield powerful enough sentence representation and achieve performance in Sentence Textual Similarity (STS) tasks on par with contrastive learning. Further in terms of unsupervised setting our generative method outperforms previous state45;of45;the45;art SimCSE on the benchmark of downstream semantic retrieval tasks.
