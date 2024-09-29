---
layout: publication
title: 'Are Electra''s Sentence Embeddings Beyond Repair? The Case Of Semantic Textual Similarity'
authors: Rep Ivan, Dukić David, Šnajder Jan
conference: "Arxiv"
year: 2024
bibkey: rep2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13130"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
While BERT produces high-quality sentence embeddings its pre-training computational cost is a significant drawback. In contrast ELECTRA delivers a cost-effective pre-training objective and downstream task performance improvements but not as performant sentence embeddings. The community tacitly stopped utilizing ELECTRAs sentence embeddings for semantic textual similarity (STS). We notice a significant drop in performance when using the ELECTRA discriminators last layer in comparison to earlier layers. We explore this drop and devise a way to repair ELECTRAs embeddings proposing a novel truncated model fine-tuning (TMFT) method. TMFT improves the Spearman correlation coefficient by over 8 points while increasing parameter efficiency on the STS benchmark dataset. We extend our analysis to various model sizes and languages. Further we discover the surprising efficacy of ELECTRAs generator model which performs on par with BERT using significantly fewer parameters and a substantially smaller embedding size. Finally we observe further boosts by combining TMFT with a word similarity task or domain adaptive pre-training.
