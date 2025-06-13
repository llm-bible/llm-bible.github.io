---
layout: publication
title: 'Attention Lens: A Tool For Mechanistically Interpreting The Attention Head Information Retrieval Mechanism'
authors: Mansi Sakarvadia, Arham Khan, Aswathy Ajith, Daniel Grzenda, Nathaniel Hudson, André Bauer, Kyle Chard, Ian Foster
conference: "Arxiv"
year: 2023
bibkey: sakarvadia2023attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.16270'}
tags: ['Attention Mechanism', 'Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Transformer-based Large Language Models (LLMs) are the state-of-the-art for
natural language tasks. Recent work has attempted to decode, by reverse
engineering the role of linear layers, the internal mechanisms by which LLMs
arrive at their final predictions for text completion tasks. Yet little is
known about the specific role of attention heads in producing the final token
prediction. We propose Attention Lens, a tool that enables researchers to
translate the outputs of attention heads into vocabulary tokens via learned
attention-head-specific transformations called lenses. Preliminary findings
from our trained lenses indicate that attention heads play highly specialized
roles in language models. The code for Attention Lens is available at
github.com/msakarvadia/AttentionLens.
