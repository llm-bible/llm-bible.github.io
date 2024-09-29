---
layout: publication
title: GIFT Generative Interpretable Fine45;tuning
authors: Savadikar Chinmay, Song Xi, Wu Tianfu
conference: "Arxiv"
year: 2023
bibkey: savadikar2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00700"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
We present Generative Interpretable Fine45;Tuning (GIFT) for parameter45;efficient fine45;tuning of pretrained Transformer backbones which can be formulated as a simple factorized matrix multiplication in the parameter space or equivalently in the activation/representation space and thus embraces built45;in interpretability. For a layer with weights ωin R^123;d95;123;out125;× d95;123;in125;125; our proposed GIFT learns the fine45;tuned weights hat123;ω125; directly from ω as hat123;ω125;=ω⋅ (I+φ95;123;d95;123;in125;× r125;⋅ψ95;123;r× d95;123;in125;125;). Theta=(φ ψ) are the learnable parameters of the two linear layers. Theta can be shared by all layers selected for fine45;tuning (e.g. all the Query and Value layers) or can be layer45;type specific (e.g. different Thetas used for Query and Value) resulting in significantly fewer trainable parameters compared to layer45;specific Low45;Rank Adaptation (LoRA). We perform comprehensive evaluations on natural language tasks (commonsense and arithmetic reasoning instruction tuning and sequence classification) and fine45;grained visual classification tasks. We obtain the best performance and parameter efficiency among baselines on commonsense reasoning instruction tuning and visual recognition benchmarks. Compared to LoRA we obtain 5.937; absolute increase in average accuracy with 53.8 times reduction of parameters on Commonsense170k using Llama45;3 (8B) and 5.437; absolute increase in the win rate with 4 times reduction of parameters using Llama45;2 (7B) during instruction tuning. Our GIFT also obtains a slightly higher win rate on instruction tuning than GPT 3.5 (Turbo 1106). We show the output of the first linear layer (i.e. ω⋅ φ) is surprisingly interpretable which can play the role of a token45;clustering head as a by45;product to localize meaningful objects/parts in images for computer vision tasks.
