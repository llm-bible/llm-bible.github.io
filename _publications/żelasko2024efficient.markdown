---
layout: publication
title: 'Emmett: Efficient Multimodal Machine Translation Training'
authors: Piotr Żelasko, Zhehuai Chen, Mengru Wang, Daniel Galvez, Oleksii Hrinchuk, Shuoyang Ding, Ke Hu, Jagadeesh Balam, Vitaly Lavrukhin, Boris Ginsburg
conference: "Arxiv"
year: 2024
bibkey: żelasko2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13523"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Tools', 'GPT', 'Applications']
---
A rising interest in the modality extension of foundation language models
warrants discussion on the most effective, and efficient, multimodal training
approach. This work focuses on neural machine translation (NMT) and proposes a
joint multimodal training regime of Speech-LLM to include automatic speech
translation (AST). We investigate two different foundation model architectures,
decoder-only GPT and encoder-decoder T5, extended with Canary-1B's speech
encoder. To handle joint multimodal training, we propose a novel training
framework called EMMeTT. EMMeTT improves training efficiency with the
following: balanced sampling across languages, datasets, and modalities;
efficient sequential data iteration; and a novel 2D bucketing scheme for
multimodal data, complemented by a batch size optimizer (OOMptimizer). We show
that a multimodal training consistently helps with both architectures.
Moreover, SALM-T5 trained with EMMeTT retains the original NMT capability while
outperforming AST baselines on four-language subsets of FLORES and FLEURS. The
resultant Multimodal Translation Model produces strong text and speech
translation results at the same time.
