---
layout: publication
title: GIFT Generative Interpretable Fine-Tuning
authors: Savadikar Chinmay, Song Xi, Wu Tianfu
conference: "Arxiv"
year: 2023
bibkey: savadikar2023gift
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00700"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We present Generative Interpretable Fine-Tuning (GIFT) for parameter-efficient fine-tuning of pretrained Transformer backbones which can be formulated as a simple factorized matrix multiplication in the parameter space or equivalently in the activation/representation space and thus embraces built-in interpretability. For a layer with weights omegain mathbbR^d_outtimes d_in our proposed GIFT learns the fine-tuned weights hatomega directly from omega as hatomega=omegacdot (mathbbI+phi_d_intimes rcdotpsi_rtimes d_in). Theta=(phi psi) are the learnable parameters of the two linear layers. Theta can be shared by all layers selected for fine-tuning (e.g. all the Query and Value layers) or can be layer-type specific (e.g. different Thetas used for Query and Value) resulting in significantly fewer trainable parameters compared to layer-specific Low-Rank Adaptation (LoRA). We perform comprehensive evaluations on natural language tasks (commonsense and arithmetic reasoning instruction tuning and sequence classification) and fine-grained visual classification tasks. We obtain the best performance and parameter efficiency among baselines on commonsense reasoning instruction tuning and visual recognition benchmarks. Compared to LoRA we obtain 5.9 absolute increase in average accuracy with 53.8 times reduction of parameters on Commonsense170k using Llama-3 (8B) and 5.4 absolute increase in the win rate with 4 times reduction of parameters using Llama-2 (7B) during instruction tuning. Our GIFT also obtains a slightly higher win rate on instruction tuning than GPT 3.5 (Turbo 1106). We show the output of the first linear layer (i.e. omegacdot phi) is surprisingly interpretable which can play the role of a token-clustering head as a by-product to localize meaningful objects/parts in images for computer vision tasks.
