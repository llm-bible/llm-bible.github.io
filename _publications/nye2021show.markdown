---
layout: publication
title: Show Your Work Scratchpads For Intermediate Computation With Language Models
authors: Nye Maxwell, Andreassen Anders Johan, Gur-ari Guy, Michalewski Henryk, Austin Jacob, Bieber David, Dohan David, Lewkowycz Aitor, Bosma Maarten, Luan David, Sutton Charles, Odena Augustus
conference: "Arxiv"
year: 2021
bibkey: nye2021show
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.00114"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
Large pre45;trained language models perform remarkably well on tasks that can be done in one pass such as generating realistic text or synthesizing computer programs. However they struggle with tasks that require unbounded multi45;step computation such as adding integers or executing programs. Surprisingly we find that these same models are able to perform complex multi45;step computations 45;45; even in the few45;shot regime 45;45; when asked to perform the operation step by step showing the results of intermediate computations. In particular we train transformers to perform multi45;step computations by asking them to emit intermediate computation steps into a scratchpad. On a series of increasingly complex tasks ranging from long addition to the execution of arbitrary programs we show that scratchpads dramatically improve the ability of language models to perform multi45;step computations.
