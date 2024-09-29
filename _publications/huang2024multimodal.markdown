---
layout: publication
title: Multimodal Task Vectors Enable Many-Shot Multimodal In-Context Learning
authors: Huang Brandon, Mitra Chancharik, Arbelle Assaf, Karlinsky Leonid, Darrell Trevor, Herzig Roei
conference: "Arxiv"
year: 2024
bibkey: huang2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15334"}
tags: ['Attention Mechanism', 'Few Shot', 'In Context Learning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The recent success of interleaved Large Multimodal Models (LMMs) in few-shot learning suggests that in-context learning (ICL) with many examples can be promising for learning new tasks. However this many-shot multimodal ICL setting has one crucial problem it is fundamentally limited by the models context length set at pretraining. The problem is especially prominent in the multimodal domain which processes both text and images requiring additional tokens. This motivates the need for a multimodal method to compress many shots into fewer tokens without finetuning. In this work we enable LMMs to perform multimodal many-shot in-context learning by leveraging Multimodal Task Vectors (MTV)--compact implicit representations of in-context examples compressed in the models attention heads. Specifically we first demonstrate the existence of such MTV in LMMs and then leverage these extracted MTV to enable many-shot in-context learning for various vision-and-language tasks. Our experiments suggest that MTV can scale in performance with the number of compressed shots and generalize to similar out-of-domain tasks without additional context length for inference.
