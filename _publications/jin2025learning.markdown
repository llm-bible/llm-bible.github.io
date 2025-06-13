---
layout: publication
title: 'Learning To Keep A Promise: Scaling Language Model Decoding Parallelism With Learned Asynchronous Decoding'
authors: Tian Jin, Ellie Y. Cheng, Zack Ankner, Nikunj Saunshi, Blake M. Elias, Amir Yazdanbakhsh, Jonathan Ragan-kelley, Suvinay Subramanian, Michael Carbin
conference: "Arxiv"
year: 2025
bibkey: jin2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11517"}
tags: ['GPT', 'RAG', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Decoding with autoregressive large language models (LLMs) traditionally
occurs sequentially, generating one token after another. An emerging line of
work explored parallel decoding by identifying and simultaneously generating
semantically independent chunks of LLM responses. However, these techniques
rely on hand-crafted heuristics tied to syntactic structures like lists and
paragraphs, making them rigid and imprecise. We present PASTA, a learning-based
system that teaches LLMs to identify semantic independence and express parallel
decoding opportunities in their own responses. At its core are PASTA-LANG and
its interpreter: PASTA-LANG is an annotation language that enables LLMs to
express semantic independence in their own responses; the language interpreter
acts on these annotations to orchestrate parallel decoding on-the-fly at
inference time. Through a two-stage finetuning process, we train LLMs to
generate PASTA-LANG annotations that optimize both response quality and
decoding speed. Evaluation on AlpacaEval, an instruction following benchmark,
shows that our approach Pareto-dominates existing methods in terms of decoding
speed and response quality; our results demonstrate geometric mean speedups
ranging from 1.21x to 1.93x with corresponding quality changes of +2.2% to
-7.1%, measured by length-controlled win rates against sequential decoding
baseline.
