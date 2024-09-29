---
layout: publication
title: COLA A Benchmark For Compositional Text45;to45;image Retrieval
authors: Ray Arijit, Radenovic Filip, Dubey Abhimanyu, Plummer Bryan A., Krishna Ranjay, Saenko Kate
conference: "Arxiv"
year: 2023
bibkey: ray2023benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03689"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Compositional reasoning is a hallmark of human visual intelligence. Yet despite the size of large vision45;language models they struggle to represent simple compositions by combining objects with their attributes. To measure this lack of compositional capability we design Cola a text45;to45;image retrieval benchmark to Compose Objects Localized with Attributes. To solve Cola a model must retrieve images with the correct configuration of attributes and objects and avoid choosing a distractor image with the same objects and attributes but in the wrong configuration. Cola contains about 1.2k composed queries of 168 objects and 197 attributes on around 30K images. Our human evaluation finds that Cola is 83.3337; accurate similar to contemporary compositionality benchmarks. Using Cola as a testbed we explore empirical modeling designs to adapt pre45;trained vision45;language models to reason compositionally. We explore 6 adaptation strategies on 2 seminal vision45;language models using compositionality45;centric test benchmarks 45; Cola and CREPE. We find the optimal adaptation strategy is to train a multi45;modal attention layer that jointly attends over the frozen pre45;trained image and language features. Surprisingly training multimodal layers on CLIP performs better than tuning a larger FLAVA model with already pre45;trained multimodal layers. Furthermore our adaptation strategy improves CLIP and FLAVA to comparable levels suggesting that training multimodal layers using contrastive attribute45;object data is key as opposed to using them pre45;trained. Lastly we show that Cola is harder than a closely related contemporary benchmark CREPE since simpler fine45;tuning strategies without multimodal layers suffice on CREPE but not on Cola. However we still see a significant gap between our best adaptation and human accuracy suggesting considerable room for further research.
