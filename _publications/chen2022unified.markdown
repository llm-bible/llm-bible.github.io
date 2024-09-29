---
layout: publication
title: Xdoc Unified Pre45;training For Cross45;format Document Understanding
authors: Chen Jingye, Lv Tengchao, Cui Lei, Zhang Cha, Wei Furu
conference: "Arxiv"
year: 2022
bibkey: chen2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02849"}
  - {name: "Code", url: "https://aka.ms/xdoc&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The surge of pre45;training has witnessed the rapid development of document understanding recently. Pre45;training and fine45;tuning framework has been effectively used to tackle texts in various formats including plain texts document texts and web texts. Despite achieving promising performance existing pre45;trained models usually target one specific document format at one time making it difficult to combine knowledge from multiple document formats. To address this we propose XDoc a unified pre45;trained model which deals with different document formats in a single model. For parameter efficiency we share backbone parameters for different formats such as the word embedding layer and the Transformer layers. Meanwhile we introduce adaptive layers with lightweight parameters to enhance the distinction across different formats. Experimental results have demonstrated that with only 36.737; parameters XDoc achieves comparable or even better performance on a variety of downstream tasks compared with the individual pre45;trained models which is cost effective for real45;world deployment. The code and pre45;trained models will be publicly available at url123;https://aka.ms/xdoc&#125;.
