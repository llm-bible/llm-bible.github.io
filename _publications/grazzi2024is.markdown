---
layout: publication
title: 'Is Mamba Capable Of In-context Learning?'
authors: Grazzi Riccardo, Siems Julien, Schrodi Simon, Brox Thomas, Hutter Frank
conference: "Arxiv"
year: 2024
bibkey: grazzi2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03170"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
State of the art foundation models such as GPT-4 perform surprisingly well at in-context learning (ICL) a variant of meta-learning concerning the learned ability to solve tasks during a neural network forward pass exploiting contextual information provided as input to the model. This useful ability emerges as a side product of the foundation models massive pretraining. While transformer models are currently the state of the art in ICL this work provides empirical evidence that Mamba a newly proposed state space model which scales better than transformers w.r.t. the input sequence length has similar ICL capabilities. We evaluated Mamba on tasks involving simple function approximation as well as more complex natural language processing problems. Our results demonstrate that across both categories of tasks Mamba closely matches the performance of transformer models for ICL. Further analysis reveals that like transformers Mamba appears to solve ICL problems by incrementally optimizing its internal representations. Overall our work suggests that Mamba can be an efficient alternative to transformers for ICL tasks involving long input sequences. This is an exciting finding in meta-learning and may enable generalizations of in-context learned AutoML algorithms (like TabPFN or Optformer) to long input sequences.
