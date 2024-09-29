---
layout: publication
title: PAGnol An Extra-Large French Generative Model
authors: Launay Julien, Tommasone Elena, Pannier Baptiste, Boniface François, Chatelain Amélie, Cappelli Alessandro, Poli Iacopo, Seddah Djamé
conference: "Arxiv"
year: 2021
bibkey: launay2021pagnol
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08554"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'GPT', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Access to large pre-trained models of varied architectures in many different languages is central to the democratization of NLP. We introduce PAGnol a collection of French GPT models. Using scaling laws we efficiently train PAGnol-XL (1.5B parameters) with the same computational budget as CamemBERT a model 13 times smaller. PAGnol-XL is the largest model trained to date for the French language. We plan to train increasingly large and performing versions of PAGnol exploring the capabilities of French extreme-scale models. For this first release we focus on the pre-training and scaling calculations underlining PAGnol. We fit a scaling law for compute for the French language and compare it with its English counterpart. We find the pre-training dataset significantly conditions the quality of the outputs with common datasets such as OSCAR leading to low-quality offensive text. We evaluate our models on discriminative and generative tasks in French comparing to other state-of-the-art French and multilingual models and reaching the state of the art in the abstract summarization task. Our research was conducted on the public GENCI Jean Zay supercomputer and our models up to the Large are made publicly available.
