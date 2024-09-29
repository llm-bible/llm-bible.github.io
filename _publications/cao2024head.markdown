---
layout: publication
title: Head-wise Shareable Attention For Large Language Models
authors: Cao Zouying, Yang Yifei, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: cao2024head
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11819"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) suffer from huge number of parameters which restricts their deployment on edge devices. Weight sharing is one promising solution that encourages weight reuse effectively reducing memory usage with less performance drop. However current weight sharing techniques primarily focus on small-scale models like BERT and employ coarse-grained sharing rules e.g. layer-wise. This becomes limiting given the prevalence of LLMs and sharing an entire layer or block obviously diminishes the flexibility of weight sharing. In this paper we present a perspective on . We further propose two memory-efficient methods that share parameters across attention heads with a specific focus on LLMs. Both of them use the same dynamic strategy to select the shared weight matrices. The first method directly reuses the pre-trained weights without retraining denoted as . The second method first post-trains with constraint on weight matrix similarity and then shares denoted as . Experimental results reveal our head-wise shared models still maintain satisfactory capabilities demonstrating the feasibility of fine-grained weight sharing applied to LLMs.
