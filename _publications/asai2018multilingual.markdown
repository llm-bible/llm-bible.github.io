---
layout: publication
title: "Multilingual Extractive Reading Comprehension By Runtime Machine Translation"
authors: Asai Akari, Eriguchi Akiko, Hashimoto Kazuma, Tsuruoka Yoshimasa
conference: "Arxiv"
year: 2018
bibkey: asai2018multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1809.03275"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques']
---
Despite recent work in Reading Comprehension (RC) progress has been mostly limited to English due to the lack of large-scale datasets in other languages. In this work we introduce the first RC system for languages without RC training data. Given a target language without RC training data and a pivot language with RC training data (e.g. English) our method leverages existing RC resources in the pivot language by combining a competitive RC model in the pivot language with an attentive Neural Machine Translation (NMT) model. We first translate the data from the target to the pivot language and then obtain an answer using the RC model in the pivot language. Finally we recover the corresponding answer in the original language using soft-alignment attention scores from the NMT model. We create evaluation sets of RC data in two non-English languages namely Japanese and French to evaluate our method. Experimental results on these datasets show that our method significantly outperforms a back-translation baseline of a state-of-the-art product-level machine translation system.
