---
layout: publication
title: Parameter45;efficient Abstractive Question Answering Over Tables Or Text
authors: Pal Vaishali, Kanoulas Evangelos, De Rijke Maarten
conference: "Arxiv"
year: 2022
bibkey: pal2022parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.03357"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
A long45;term ambition of information seeking QA systems is to reason over multi45;modal contexts and generate natural answers to user queries. Today memory intensive pre45;trained language models are adapted to downstream tasks such as QA by fine45;tuning the model on QA data in a specific modality like unstructured text or structured tables. To avoid training such memory45;hungry models while utilizing a uniform architecture for each modality parameter45;efficient adapters add and train small task45;specific bottle45;neck layers between transformer layers. In this work we study parameter45;efficient abstractive QA in encoder45;decoder models over structured tabular data and unstructured textual data using only 1.537; additional parameters for each modality. We also ablate over adapter layers in both encoder and decoder modules to study the efficiency45;performance trade45;off and demonstrate that reducing additional trainable parameters down to 0.737;45;1.037; leads to comparable results. Our models out45;perform current state45;of45;the45;art models on tabular QA datasets such as Tablesum and FeTaQA and achieve comparable performance on a textual QA dataset such as NarrativeQA using significantly less trainable parameters than fine45;tuning.
