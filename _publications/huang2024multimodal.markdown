---
layout: publication
title: Multimodal Task Vectors Enable Many45;shot Multimodal In45;context Learning
authors: Huang Brandon, Mitra Chancharik, Arbelle Assaf, Karlinsky Leonid, Darrell Trevor, Herzig Roei
conference: "Arxiv"
year: 2024
bibkey: huang2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15334"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The recent success of interleaved Large Multimodal Models (LMMs) in few45;shot learning suggests that in45;context learning (ICL) with many examples can be promising for learning new tasks. However this many45;shot multimodal ICL setting has one crucial problem it is fundamentally limited by the models context length set at pretraining. The problem is especially prominent in the multimodal domain which processes both text and images requiring additional tokens. This motivates the need for a multimodal method to compress many shots into fewer tokens without finetuning. In this work we enable LMMs to perform multimodal many45;shot in45;context learning by leveraging Multimodal Task Vectors (MTV)45;45;compact implicit representations of in45;context examples compressed in the models attention heads. Specifically we first demonstrate the existence of such MTV in LMMs and then leverage these extracted MTV to enable many45;shot in45;context learning for various vision45;and45;language tasks. Our experiments suggest that MTV can scale in performance with the number of compressed shots and generalize to similar out45;of45;domain tasks without additional context length for inference.
