---
layout: publication
title: Pre45;training Intent45;aware Encoders For Zero45; And Few45;shot Intent Classification
authors: Sung Mujeen, Gung James, Mansimov Elman, Pappas Nikolaos, Shu Raphael, Romeo Salvatore, Zhang Yi, Castelli Vittorio
conference: "Arxiv"
year: 2023
bibkey: sung2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14827"}
tags: ['Applications', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Intent classification (IC) plays an important role in task45;oriented dialogue systems. However IC models often generalize poorly when training without sufficient annotated examples for each user intent. We propose a novel pre45;training method for text encoders that uses contrastive learning with intent psuedo45;labels to produce embeddings that are well45;suited for IC tasks reducing the need for manual annotations. By applying this pre45;training strategy we also introduce Pre45;trained Intent45;aware Encoder (PIE) which is designed to align encodings of utterances with their intent names. Specifically we first train a tagger to identify key phrases within utterances that are crucial for interpreting intents. We then use these extracted phrases to create examples for pre45;training a text encoder in a contrastive manner. As a result our PIE model achieves up to 5.437; and 4.037; higher accuracy than the previous state45;of45;the45;art text encoder for the N45;way zero45; and one45;shot settings on four IC datasets.
