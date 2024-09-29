---
layout: publication
title: "PSLM: Parallel Generation Of Text And Speech With Llms For Low-latency Spoken Dialogue Systems"
authors: Mitsui Kentaro, Mitsuda Koh, Wakatsuki Toshiaki, Hono Yukiya, Sawada Kei
conference: "Arxiv"
year: 2024
bibkey: mitsui2024parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12428"}
tags: ['Applications', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal language models that process both text and speech have a potential for applications in spoken dialogue systems. However current models face two major challenges in response generation latency (1) generating a spoken response requires the prior generation of a written response and (2) speech sequences are significantly longer than text sequences. This study addresses these issues by extending the input and output sequences of the language model to support the parallel generation of text and speech. Our experiments on spoken question answering tasks demonstrate that our approach improves latency while maintaining the quality of response content. Additionally we show that latency can be further reduced by generating speech in multiple sequences. Demo samples are available at https://rinnakk.github.io/research/publications/PSLM."
