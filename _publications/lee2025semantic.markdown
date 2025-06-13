---
layout: publication
title: 'Semantic Aware Linear Transfer By Recycling Pre-trained Language Models For Cross-lingual Transfer'
authors: Seungyoon Lee, Seongtae Hong, Hyeonseok Moon, Heuiseok Lim
conference: "Arxiv"
year: 2025
bibkey: lee2025semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10945"}
tags: ['Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) increasingly incorporate multilingual capabilities, fueling the demand to transfer them into target language-specific models. However, most approaches, which blend the source model's embedding by replacing the source vocabulary with the target language-specific vocabulary, may constrain expressive capacity in the target language since the source model is predominantly trained on English data. In this paper, we propose Semantic Aware Linear Transfer (SALT), a novel cross-lingual transfer technique that recycles embeddings from target language Pre-trained Language Models (PLMs) to transmit the deep representational strengths of PLM-derived embedding to LLMs. SALT derives unique regression lines based on the similarity in the overlap of the source and target vocabularies, to handle each non-overlapping token's embedding space. Our extensive experiments show that SALT significantly outperforms other transfer methods and achieves lower loss with accelerating faster convergence during language adaptation. Notably, SALT obtains remarkable performance in cross-lingual understanding setups compared to other methods. Furthermore, we highlight the scalable use of PLMs to enhance the functionality of contemporary LLMs by conducting experiments with varying architectures.
