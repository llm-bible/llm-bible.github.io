---
layout: publication
title: Moeut Mixture45;of45;experts Universal Transformers
authors: Csordás Róbert, Irie Kazuki, Schmidhuber Jürgen, Potts Christopher, Manning Christopher D.
conference: "Arxiv"
year: 2024
bibkey: csordás2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16039"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Previous work on Universal Transformers (UTs) has demonstrated the importance of parameter sharing across layers. By allowing recurrence in depth UTs have advantages over standard Transformers in learning compositional generalizations but layer45;sharing comes with a practical limitation of parameter45;compute ratio it drastically reduces the parameter count compared to the non45;shared model with the same dimensionality. Naively scaling up the layer size to compensate for the loss of parameters makes its computational resource requirements prohibitive. In practice no previous work has succeeded in proposing a shared45;layer Transformer design that is competitive in parameter count45;dominated tasks such as language modeling. Here we propose MoEUT (pronounced moot) an effective mixture45;of45;experts (MoE)45;based shared45;layer Transformer architecture which combines several recent advances in MoEs for both feedforward and attention layers of standard Transformers together with novel layer45;normalization and grouping schemes that are specific and crucial to UTs. The resulting UT model for the first time slightly outperforms standard Transformers on language modeling tasks such as BLiMP and PIQA while using significantly less compute and memory.
