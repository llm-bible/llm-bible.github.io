---
layout: publication
title: Efficient Pre45;training For Localized Instruction Generation Of Videos
authors: Batra Anil, Moltisanti Davide, Sevilla-lara Laura, Rohrbach Marcus, Keller Frank
conference: "Arxiv"
year: 2023
bibkey: batra2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15964"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Procedural videos exemplified by recipe demonstrations are instrumental in conveying step45;by45;step instructions. However understanding such videos is challenging as it involves the precise localization of steps and the generation of textual instructions. Manually annotating steps and writing instructions is costly which limits the size of current datasets and hinders effective learning. Leveraging large but noisy video45;transcript datasets for pre45;training can boost performance but demands significant computational resources. Furthermore transcripts contain irrelevant content and differ in style from human45;written instructions. To mitigate these issues we propose a novel technique Sieve45;amp;45;Swap to automatically generate high45;quality training data for the recipe domain (i) Sieve filters irrelevant transcripts and (ii) Swap acquires high45;quality text by replacing transcripts with human45;written instruction from a text45;only recipe dataset. The resulting dataset is three orders of magnitude smaller than current web45;scale datasets but enables efficient training of large45;scale models. Alongside Sieve45;amp;45;Swap we propose Procedure Transformer (ProcX) a model for end45;to45;end step localization and instruction generation for procedural videos. When pre45;trained on our curated dataset this model achieves state45;of45;the45;art performance on YouCook2 and Tasty while using a fraction of the training data. We have released code and dataset.
