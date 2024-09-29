---
layout: publication
title: A Multilingual Modeling Method For Span45;extraction Reading Comprehension
authors: Wu Gaochen, Xu Bin, Chang Dejie, Liu Bangchang
conference: "Arxiv"
year: 2021
bibkey: wu2021multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.14880"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Tools', 'Training Techniques']
---
Span45;extraction reading comprehension models have made tremendous advances enabled by the availability of large45;scale high45;quality training datasets. Despite such rapid progress and widespread application extractive reading comprehension datasets in languages other than English remain scarce and creating such a sufficient amount of training data for each language is costly and even impossible. An alternative to creating large45;scale high45;quality monolingual span45;extraction training datasets is to develop multilingual modeling approaches and systems which can transfer to the target language without requiring training data in that language. In this paper in order to solve the scarce availability of extractive reading comprehension training data in the target language we propose a multilingual extractive reading comprehension approach called XLRC by simultaneously modeling the existing extractive reading comprehension training data in a multilingual environment using self45;adaptive attention and multilingual attention. Specifically we firstly construct multilingual parallel corpora by translating the existing extractive reading comprehension datasets (i.e. CMRC 2018) from the target language (i.e. Chinese) into different language families (i.e. English). Secondly to enhance the final target representation we adopt self45;adaptive attention (SAA) to combine self45;attention and inter45;attention to extract the semantic relations from each pair of the target and source languages. Furthermore we propose multilingual attention (MLA) to learn the rich knowledge from various language families. Experimental results show that our model outperforms the state45;of45;the45;art baseline (i.e. RoBERTa95;Large) on the CMRC 2018 task which demonstrate the effectiveness of our proposed multi45;lingual modeling approach and show the potentials in multilingual NLP tasks.
