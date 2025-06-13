---
layout: publication
title: 'Semantically Grounded Qformer For Efficient Vision Language Understanding'
authors: Moulik Choraria, Xinbo Wu, Sourya Basu, Nitesh Sekhar, Yue Wu, Xu Zhang, Prateek Singhal, Lav R. Varshney
conference: "Arxiv"
year: 2023
bibkey: choraria2023semantically
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.07449'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Multimodal Models', 'Pretraining Methods']
---
General purpose Vision Language Models (VLMs) have received tremendous
interest in recent years, owing to their ability to learn rich vision-language
correlations as well as their broad zero-shot competencies. One immensely
popular line of work utilizes frozen unimodal models, by bridging vision
representations to language using a trainable module called the QFormer.
However, this method relies heavily on large-scale multimodal pretraining with
huge computational overheads. To that end, we propose a more efficient
framework for QFormer-based vision-language alignment. Our key idea relies on
the observation that QFormer latents correspond more strongly to the frozen
LLM's intermediate latent space. Consequently, instead of using QFormer latents
as inputs to the LLM, we alter the framework by using the latents to directly
condition the LLM latent space for image-to-text generation. We demonstrate the
effectiveness of our approach against existing baselines in improving the
efficiency of vision-language pretraining.
