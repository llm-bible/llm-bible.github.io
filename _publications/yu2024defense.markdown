---
layout: publication
title: In Defense Of RAG In The Era Of Long45;context Language Models
authors: Yu Tan, Xu Anbang, Akkiraju Rama
conference: "Arxiv"
year: 2024
bibkey: yu2024defense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01666"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
Overcoming the limited context limitations in early45;generation LLMs retrieval45;augmented generation (RAG) has been a reliable solution for context45;based answer generation in the past. Recently the emergence of long45;context LLMs allows the models to incorporate much longer text sequences making RAG less attractive. Recent studies show that long45;context LLMs significantly outperform RAG in long45;context applications. Unlike the existing works favoring the long45;context LLM over RAG we argue that the extremely long context in LLMs suffers from a diminished focus on relevant information and leads to potential degradation in answer quality. This paper revisits the RAG in long45;context answer generation. We propose an order45;preserve retrieval45;augmented generation (OP45;RAG) mechanism which significantly improves the performance of RAG for long45;context question45;answer applications. With OP45;RAG as the number of retrieved chunks increases the answer quality initially rises and then declines forming an inverted U45;shaped curve. There exist sweet points where OP45;RAG could achieve higher answer quality with much less tokens than long45;context LLM taking the whole context as input. Extensive experiments on public benchmark demonstrate the superiority of our OP45;RAG.
