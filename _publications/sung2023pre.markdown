---
layout: publication
title: "Pre-training Intent-aware Encoders For Zero- And Few-shot Intent Classification"
authors: Sung Mujeen, Gung James, Mansimov Elman, Pappas Nikolaos, Shu Raphael, Romeo Salvatore, Zhang Yi, Castelli Vittorio
conference: "Arxiv"
year: 2023
bibkey: sung2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14827"}
tags: ['Applications', 'Few Shot', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Intent classification (IC) plays an important role in task-oriented dialogue systems. However IC models often generalize poorly when training without sufficient annotated examples for each user intent. We propose a novel pre-training method for text encoders that uses contrastive learning with intent psuedo-labels to produce embeddings that are well-suited for IC tasks reducing the need for manual annotations. By applying this pre-training strategy we also introduce Pre-trained Intent-aware Encoder (PIE) which is designed to align encodings of utterances with their intent names. Specifically we first train a tagger to identify key phrases within utterances that are crucial for interpreting intents. We then use these extracted phrases to create examples for pre-training a text encoder in a contrastive manner. As a result our PIE model achieves up to 5.437; and 4.037; higher accuracy than the previous state-of-the-art text encoder for the N-way zero- and one-shot settings on four IC datasets.
