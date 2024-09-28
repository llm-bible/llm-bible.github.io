---
layout: publication
title: Hiformer Heterogeneous Feature Interactions Learning with Transformers for Recommender Systems
authors: Gui Huan, Wang Ruoxi, Yin Ke, Jin Long, Kula Maciej, Xu Taibai, Hong Lichan, Chi Ed H.
conference: "Arxiv"
year: 2023
bibkey: gui2023hiformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05884"}
tags: ['ARXIV', 'Applications', 'Pruning', 'Tools', 'Transformer']
---
Learning feature interaction is the critical backbone to building recommender systems. In web-scale applications learning feature interaction is extremely challenging due to the sparse and large input feature space; meanwhile manually crafting effective feature interactions is infeasible because of the exponential solution space. We propose to leverage a Transformer-based architecture with attention layers to automatically capture feature interactions. Transformer architectures have witnessed great success in many domains such as natural language processing and computer vision. However there has not been much adoption of Transformer architecture for feature interaction modeling in industry. We aim at closing the gap. We identify two key challenges for applying the vanilla Transformer architecture to web-scale recommender systems (1) Transformer architecture fails to capture the heterogeneous feature interactions in the self-attention layer; (2) The serving latency of Transformer architecture might be too high to be deployed in web-scale recommender systems. We first propose a heterogeneous self-attention layer which is a simple yet effective modification to the self-attention layer in Transformer to take into account the heterogeneity of feature interactions. We then introduce (eterogeneous nteraction Trans) to further improve the model expressiveness. With low-rank approximation and model pruning hiformer enjoys fast inference for online deployment. Extensive offline experiment results corroborates the effectiveness and efficiency of the model. We have successfully deployed the model to a real world large scale App ranking model at Google Play with significant improvement in key engagement metrics (up to +2.66).
