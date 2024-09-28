---
layout: publication
title: AttnLRP Attention-Aware Layer-Wise Relevance Propagation for Transformers
authors: Achtibat Reduan, Hatefi Sayed Mohammad Vakilzadeh, Dreyer Maximilian, Jain Aakriti, Wiegand Thomas, Lapuschkin Sebastian, Samek Wojciech
conference: "Arxiv"
year: 2024
bibkey: achtibat2024attnlrp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05602"}
  - {name: "Code", url: "https://github.com/rachtibat/LRP-eXplains-Transformers"}
tags: ['Model Architecture', 'Transformer', 'Has Code', 'Arxiv']
---
Large Language Models are prone to biased predictions and hallucinations underlining the paramount importance of understanding their model-internal reasoning process. However achieving faithful attributions for the entirety of a black-box transformer model and maintaining computational efficiency is an unsolved challenge. By extending the Layer-wise Relevance Propagation attribution method to handle attention layers we address these challenges effectively. While partial solutions exist our method is the first to faithfully and holistically attribute not only input but also latent representations of transformer models with the computational efficiency similar to a single backward pass. Through extensive evaluations against existing methods on LLaMa 2 Mixtral 8x7b Flan-T5 and vision transformer architectures we demonstrate that our proposed approach surpasses alternative methods in terms of faithfulness and enables the understanding of latent representations opening up the door for concept-based explanations. We provide an LRP library at https://github.com/rachtibat/LRP-eXplains-Transformers.
