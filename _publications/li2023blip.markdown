---
layout: publication
title: BLIP45;2 Bootstrapping Language45;image Pre45;training With Frozen Image Encoders And Large Language Models
authors: Junnan Li, Dongxu Li, Silvio Savarese, Steven Hoi
conference: "Arxiv"
year: 2023
bibkey: li2023blip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2301.12597v3"}
tags: ['Applications', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The cost of vision45;and45;language pre45;training has become increasingly prohibitive due to end45;to45;end training of large45;scale models. This paper proposes BLIP45;2 a generic and efficient pre45;training strategy that bootstraps vision45;language pre45;training from off45;the45;shelf frozen pre45;trained image encoders and frozen large language models. BLIP45;2 bridges the modality gap with a lightweight Querying Transformer which is pre45;trained in two stages. The first stage bootstraps vision45;language representation learning from a frozen image encoder. The second stage bootstraps vision45;to45;language generative learning from a frozen language model. BLIP45;2 achieves state45;of45;the45;art performance on various vision45;language tasks despite having significantly fewer trainable parameters than existing methods. For example our model outperforms Flamingo80B by 8.737; on zero45;shot VQAv2 with 54x fewer trainable parameters. We also demonstrate the models emerging capabilities of zero45;shot image45;to45;text generation that can follow natural language instructions.
