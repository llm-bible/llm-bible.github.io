---
layout: publication
title: 'Attnlrp: Attention-aware Layer-wise Relevance Propagation For Transformers'
authors: Reduan Achtibat, Sayed Mohammad Vakilzadeh Hatefi, Maximilian Dreyer, Aakriti Jain, Thomas Wiegand, Sebastian Lapuschkin, Wojciech Samek
conference: "Arxiv"
year: 2024
bibkey: achtibat2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05602"}
  - {name: "Code", url: "https://github.com/rachtibat/LRP-eXplains-Transformers"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Large Language Models are prone to biased predictions and hallucinations,
underlining the paramount importance of understanding their model-internal
reasoning process. However, achieving faithful attributions for the entirety of
a black-box transformer model and maintaining computational efficiency is an
unsolved challenge. By extending the Layer-wise Relevance Propagation
attribution method to handle attention layers, we address these challenges
effectively. While partial solutions exist, our method is the first to
faithfully and holistically attribute not only input but also latent
representations of transformer models with the computational efficiency similar
to a single backward pass. Through extensive evaluations against existing
methods on LLaMa 2, Mixtral 8x7b, Flan-T5 and vision transformer architectures,
we demonstrate that our proposed approach surpasses alternative methods in
terms of faithfulness and enables the understanding of latent representations,
opening up the door for concept-based explanations. We provide an LRP library
at https://github.com/rachtibat/LRP-eXplains-Transformers.
