---
layout: publication
title: Sentence Representation Learning With Generative Objective Rather Than Contrastive Objective
authors: Wu Bohong, Zhao Hai
conference: "Arxiv"
year: 2022
bibkey: wu2022sentence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08474"}
  - {name: "Code", url: "https://github.com/chengzhipanpan/PaSeR"}
tags: ['Attention Mechanism', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Though offering amazing contextualized token45;level representations current pre45;trained language models take less attention on accurately acquiring sentence45;level representation during their self45;supervised pre45;training. However contrastive objectives which dominate the current sentence representation learning bring little linguistic interpretability and no performance guarantee on downstream semantic tasks. We instead propose a novel generative self45;supervised learning objective based on phrase reconstruction. To overcome the drawbacks of previous generative methods we carefully model intra45;sentence structure by breaking down one sentence into pieces of important phrases. Empirical studies show that our generative learning achieves powerful enough performance improvement and outperforms the current state45;of45;the45;art contrastive methods not only on the STS benchmarks but also on downstream semantic retrieval and reranking tasks. Our code is available at https://github.com/chengzhipanpan/PaSeR.
