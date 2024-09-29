---
layout: publication
title: Class Incremental Learning With Pre45;trained Vision45;language Models
authors: Liu Xialei, Cao Xusheng, Lu Haori, Xiao Jia-wen, Bagdanov Andrew D., Cheng Ming-ming
conference: "Arxiv"
year: 2023
bibkey: liu2023class
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20348"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
With the advent of large45;scale pre45;trained models interest in adapting and exploiting them for continual learning scenarios has grown. In this paper we propose an approach to exploiting pre45;trained vision45;language models (e.g. CLIP) that enables further adaptation instead of only using zero45;shot learning of new tasks. We augment a pre45;trained CLIP model with additional layers after the Image Encoder or before the Text Encoder. We investigate three different strategies a Linear Adapter a Self45;attention Adapter each operating on the image embedding and Prompt Tuning which instead modifies prompts input to the CLIP text encoder. We also propose a method for parameter retention in the adapter layers that uses a measure of parameter importance to better maintain stability and plasticity during incremental learning. Our experiments demonstrate that the simplest solution 45;45; a single Linear Adapter layer with parameter retention 45;45; produces the best results. Experiments on several conventional benchmarks consistently show a significant margin of improvement over the current state45;of45;the45;art.
