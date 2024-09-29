---
layout: publication
title: Attention Lens A Tool for Mechanistically Interpreting the Attention Head Information Retrieval Mechanism
authors: Sakarvadia Mansi, Khan Arham, Ajith Aswathy, Grzenda Daniel, Hudson Nathaniel, Bauer André, Chard Kyle, Foster Ian
conference: "Arxiv"
year: 2023
bibkey: sakarvadia2023attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16270"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer-based Large Language Models (LLMs) are the state-of-the-art for natural language tasks. Recent work has attempted to decode by reverse engineering the role of linear layers the internal mechanisms by which LLMs arrive at their final predictions for text completion tasks. Yet little is known about the specific role of attention heads in producing the final token prediction. We propose Attention Lens a tool that enables researchers to translate the outputs of attention heads into vocabulary tokens via learned attention-head-specific transformations called lenses. Preliminary findings from our trained lenses indicate that attention heads play highly specialized roles in language models. The code for Attention Lens is available at github.com/msakarvadia/AttentionLens.
