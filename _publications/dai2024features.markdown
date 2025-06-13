---
layout: publication
title: 'DENIAHL: In-context Features Influence LLM Needle-in-a-haystack Abilities'
authors: Hui Dai, Dan Pechi, Xinyi Yang, Garvit Banga, Raghav Mantri
conference: "Arxiv"
year: 2024
bibkey: dai2024features
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19360'}
tags: ['GPT', 'Tools', 'Model Architecture']
---
The Needle-in-a-haystack (NIAH) test is a general task used to assess
language models' (LMs') abilities to recall particular information from long
input context. This framework however does not provide a means of analyzing
what factors, beyond context length, contribute to LMs' abilities or
inabilities to separate and recall needles from their haystacks. To provide a
systematic means of assessing what features contribute to LMs' NIAH
capabilities, we developed a synthetic benchmark called DENIAHL (Data-oriented
Evaluation of NIAH for LLM's). Our work expands on previous NIAH studies by
ablating NIAH features beyond typical context length including data type, size,
and patterns. We find stark differences between GPT-3.5 and LLaMA 2-7B's
performance on DENIAHL, and drops in recall performance when features like item
size are increased, and to some degree when data type is changed from numbers
to letters. This has implications for increasingly large context models,
demonstrating factors beyond item-number impact NIAH capabilities.
