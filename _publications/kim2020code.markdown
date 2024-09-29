---
layout: publication
title: Code Prediction By Feeding Trees To Transformers
authors: Kim Seohyun, Zhao Jinman, Tian Yuchi, Chandra Satish
conference: "Arxiv"
year: 2020
bibkey: kim2020code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2003.13848"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
We advance the state45;of45;the45;art in the accuracy of code prediction (next token prediction) used in autocomplete systems. First we report that using the recently proposed Transformer architecture even out45;of45;the45;box outperforms previous neural and non45;neural systems for code prediction. We then show that by making the Transformer architecture aware of the syntactic structure of code we further increase the margin by which a Transformer45;based system outperforms previous systems. With this it outperforms the accuracy of an RNN45;based system (similar to Hellendoorn et al. 2018) by 18.337; the Deep3 system (Raychev et al 2016) by 14.137; and an adaptation of Code2Seq (Alon et al. 2018) for code prediction by 14.437;. We present in the paper several ways of communicating the code structure to the Transformer which is fundamentally built for processing sequence data. We provide a comprehensive experimental evaluation of our proposal along with alternative design choices on a standard Python dataset as well as on a Facebook internal Python corpus. Our code and data preparation pipeline will be available in open source.
