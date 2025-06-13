---
layout: publication
title: 'Mesa-extrapolation: A Weave Position Encoding Method For Enhanced Extrapolation In Llms'
authors: Xin Ma, Yang Liu, Jingjing Liu, Xiaoxu Ma
conference: "Arxiv"
year: 2024
bibkey: ma2024mesa
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15859'}
  - {name: "Code", url: 'https://github.com/soacker/Mesa-Extrapolation'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs), although having revolutionized many fields,
still suffer from the challenging extrapolation problem, where the inference
ability of LLMs sharply declines beyond their max training lengths. In this
work, we conduct a theoretical analysis to better understand why No Position
Encoding (NoPE) fails outside its effective range, as well as examining the
power of Position Encoding (PE) in this context. Our findings reveal that with
meticulous weave position, PE can indeed be extended beyond effective range.
Our theorems establish that LLMs equipped with weave PE can achieve improved
extrapolation performance without additional cost. Furthermore, we introduce a
novel weave PE method, Mesa-Extrapolation, which utilizes a chunk-based
triangular attention matrix and applies Stair PE to manage the final chunk.
This method not only retains competitive performance but also offers
substantial benefits such as significantly reduced memory demand and faster
inference speed. Extensive experiments validate the effectiveness of
Mesa-Extrapolation, demonstrating its potential as a scalable solution to
enhancing LLMs applicative reach. Our code is available at
\url\{https://github.com/soacker/Mesa-Extrapolation\}.
