---
layout: publication
title: RHO (ρ) Reducing Hallucination In Open45;domain Dialogues With Knowledge Grounding
authors: Ji Ziwei, Liu Zihan, Lee Nayeon, Yu Tiezheng, Wilie Bryan, Zeng Min, Fung Pascale
conference: "Arxiv"
year: 2022
bibkey: ji2022rho
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.01588"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Dialogue systems can leverage large pre45;trained language models and knowledge to generate fluent and informative responses. However these models are still prone to produce hallucinated responses not supported by the input source which greatly hinders their application. The heterogeneity between external knowledge and dialogue context challenges representation learning and source integration and further contributes to unfaithfulness. To handle this challenge and generate more faithful responses this paper presents RHO (ρ) utilizing the representations of linked entities and relation predicates from a knowledge graph (KG). We propose (1) local knowledge grounding to combine textual embeddings with the corresponding KG embeddings; and (2) global knowledge grounding to equip RHO with multi45;hop reasoning abilities via the attention mechanism. In addition we devise a response re45;ranking technique based on walks over KG sub45;graphs for better conversational reasoning. Experimental results on OpenDialKG show that our approach significantly outperforms state45;of45;the45;art methods on both automatic and human evaluation by a large margin especially in hallucination reduction (17.5437; in FeQA).
