---
layout: publication
title: You Only Forward Once Prediction And Rationalization In A Single Forward Pass
authors: Jiang Han, Duan Junwen, Qu Zhe, Wang Jianxin
conference: "Arxiv"
year: 2023
bibkey: jiang2023you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02344"}
tags: ['BERT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Survey Paper', 'Tools']
---
Unsupervised rationale extraction aims to extract concise and contiguous text snippets to support model predictions without any annotated rationale. Previous studies have used a two45;phase framework known as the Rationalizing Neural Prediction (RNP) framework which follows a generate45;then45;predict paradigm. They assumed that the extracted explanation called rationale should be sufficient to predict the golden label. However the assumption above deviates from the original definition and is too strict to perform well. Furthermore these two45;phase models suffer from the interlocking problem and spurious correlations. To solve the above problems we propose a novel single45;phase framework called You Only Forward Once (YOFO) derived from a relaxed version of rationale where rationales aim to support model predictions rather than make predictions. In our framework A pre45;trained language model like BERT is deployed to simultaneously perform prediction and rationalization with less impact from interlocking or spurious correlations. Directly choosing the important tokens in an unsupervised manner is intractable. Instead of directly choosing the important tokens YOFO gradually removes unimportant tokens during forward propagation. Through experiments on the BeerAdvocate and Hotel Review datasets we demonstrate that our model is able to extract rationales and make predictions more accurately compared to RNP45;based models. We observe an improvement of up to 18.437; in token45;level F1 compared to previous state45;of45;the45;art methods. We also conducted analyses and experiments to explore the extracted rationales and token decay strategies. The results show that YOFO can extract precise and important rationales while removing unimportant tokens in the middle part of the model.
