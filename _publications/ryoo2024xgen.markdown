---
layout: publication
title: 'Xgen-mm-vid (blip-3-video): You Only Need 32 Tokens To Represent A Video Even In Vlms'
authors: Michael S. Ryoo, Honglu Zhou, Shrikant Kendre, Can Qin, Le Xue, Manli Shu, Silvio Savarese, Ran Xu, Caiming Xiong, Juan Carlos Niebles
conference: "Arxiv"
year: 2024
bibkey: ryoo2024xgen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16267"}
  - {name: "Code", url: "https://www.salesforceairesearch.com/opensource/xGen-MM-Vid/index.html"}
tags: ['Multimodal Models', 'Has Code', 'Reinforcement Learning']
---
We present xGen-MM-Vid (BLIP-3-Video): a multimodal language model for
videos, particularly designed to efficiently capture temporal information over
multiple frames. BLIP-3-Video takes advantage of the 'temporal encoder' in
addition to the conventional visual tokenizer, which maps a sequence of tokens
over multiple frames into a compact set of visual tokens. This enables
BLIP3-Video to use much fewer visual tokens than its competing models (e.g., 32
vs. 4608 tokens). We explore different types of temporal encoders, including
learnable spatio-temporal pooling as well as sequential models like Token
Turing Machines. We experimentally confirm that BLIP-3-Video obtains video
question-answering accuracies comparable to much larger state-of-the-art models
(e.g., 34B), while being much smaller (i.e., 4B) and more efficient by using
fewer visual tokens. The project website is at
https://www.salesforceairesearch.com/opensource/xGen-MM-Vid/index.html
