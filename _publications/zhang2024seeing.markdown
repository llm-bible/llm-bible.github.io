---
layout: publication
title: 'Seeing Clearly By Layer Two: Enhancing Attention Heads To Alleviate Hallucination In Lvlms'
authors: Xiaofeng Zhang, Yihao Quan, Chaochen Gu, Chen Shen, Xiaosong Yuan, Shaotian Yan, Hao Cheng, Kaijie Wu, Jieping Ye
conference: "Arxiv"
year: 2024
bibkey: zhang2024seeing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.09968'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
The hallucination problem in multimodal large language models (MLLMs) remains
a common issue. Although image tokens occupy a majority of the input sequence
of MLLMs, there is limited research to explore the relationship between image
tokens and hallucinations. In this paper, we analyze the distribution of
attention scores for image tokens across each layer and head of the model,
revealing an intriguing and common phenomenon: most hallucinations are closely
linked to the pattern of attention sinks in the self-attention matrix of image
tokens, where shallow layers exhibit dense attention sinks and deeper layers
show sparse attention sinks. We further analyze the attention heads of
different layers and find that heads with high-density attention sink in the
image part play a positive role in alleviating hallucinations. In this paper,
we propose a training-free method named \textcolor\{red\}\{\textbf\{E\}\}nhancing
\textcolor\{red\}\{\textbf\{A\}\}ttention \textcolor\{red\}\{\textbf\{H\}\}eads (EAH), an
approach designed to enhance the convergence of image tokens attention sinks in
the shallow layers. EAH identifies the attention head that shows the vision
sink in a shallow layer and extracts its attention matrix. This attention map
is then broadcast to other heads in the layer, thereby strengthening the layer
to pay more attention to the image itself. With extensive experiments, EAH
shows significant hallucination-mitigating performance on different MLLMs and
metrics, proving its effectiveness and generality.
