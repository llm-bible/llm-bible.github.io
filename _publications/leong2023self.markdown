---
layout: publication
title: Self45;detoxifying Language Models Via Toxification Reversal
authors: Leong Chak Tou, Cheng Yi, Wang Jiashuo, Wang Jian, Li Wenjie
conference: "Arxiv"
year: 2023
bibkey: leong2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09573"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Language model detoxification aims to minimize the risk of generating offensive or harmful content in pretrained language models (PLMs) for safer deployment. Existing methods can be roughly categorized as finetuning45;based and decoding45;based. However the former is often resource45;intensive while the latter relies on additional components and potentially compromises the generation fluency. In this paper we propose a more lightweight approach that enables the PLM itself to achieve self45;detoxification. Our method is built upon the observation that prepending a negative steering prompt can effectively induce PLMs to generate toxic content. At the same time we are inspired by the recent research in the interpretability field which formulates the evolving contextualized representations within the PLM as an information stream facilitated by the attention layers. Drawing on this idea we devise a method to identify the toxification direction from the normal generation process to the one prompted with the negative prefix and then steer the generation to the reversed direction by manipulating the information movement within the attention layers. Experimental results show that our approach without any fine45;tuning or extra components can achieve comparable performance with state45;of45;the45;art methods.
