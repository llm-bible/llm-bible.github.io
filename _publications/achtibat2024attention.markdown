---
layout: publication
title: Attnlrp Attention45;aware Layer45;wise Relevance Propagation For Transformers
authors: Achtibat Reduan, Hatefi Sayed Mohammad Vakilzadeh, Dreyer Maximilian, Jain Aakriti, Wiegand Thomas, Lapuschkin Sebastian, Samek Wojciech
conference: "Arxiv"
year: 2024
bibkey: achtibat2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05602"}
  - {name: "Code", url: "https://github.com/rachtibat/LRP&#45;eXplains&#45;Transformers"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Ethics And Bias', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Large Language Models are prone to biased predictions and hallucinations underlining the paramount importance of understanding their model45;internal reasoning process. However achieving faithful attributions for the entirety of a black45;box transformer model and maintaining computational efficiency is an unsolved challenge. By extending the Layer45;wise Relevance Propagation attribution method to handle attention layers we address these challenges effectively. While partial solutions exist our method is the first to faithfully and holistically attribute not only input but also latent representations of transformer models with the computational efficiency similar to a single backward pass. Through extensive evaluations against existing methods on LLaMa 2 Mixtral 8x7b Flan45;T5 and vision transformer architectures we demonstrate that our proposed approach surpasses alternative methods in terms of faithfulness and enables the understanding of latent representations opening up the door for concept45;based explanations. We provide an LRP library at https://github.com/rachtibat/LRP&#45;eXplains&#45;Transformers.
