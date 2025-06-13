---
layout: publication
title: 'LLM Modules: Knowledge Transfer From A Large To A Small Model Using Enhanced Cross-attention'
authors: Konstantin Almaty, Kazakhstan Kolomeitsev
conference: "Arxiv"
year: 2025
bibkey: kolomeitsev2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08213"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Distillation']
---
In this work, we propose an architecture of LLM Modules that enables the
transfer of knowledge from a large pre-trained model to a smaller model using
an Enhanced Cross-Attention mechanism. In the proposed scheme, the Qwen2-1.5B
model is frozen and its representations are passed through specially designed
attention layers to the GPT-Neo-125M model, which is trained on limited
computational resources. Experimental results on the Bespoke-Stratos-17k
dataset demonstrate that after 15 epochs of training, the combined model
generates responses comparable in quality to those obtained by distillation. We
discuss the advantages of the modular approach, provide examples of input
queries and comparative analysis, and outline prospects for further extension
of the method.
