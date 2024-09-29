---
layout: publication
title: Fantastically Ordered Prompts And Where To Find Them Overcoming Few45;shot Prompt Order Sensitivity
authors: Lu Yao, Bartolo Max, Moore Alastair, Riedel Sebastian, Stenetorp Pontus
conference: "Arxiv"
year: 2021
bibkey: lu2021fantastically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.08786"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
When primed with only a handful of training samples very large pretrained language models such as GPT45;3 have shown competitive results when compared to fully45;supervised fine45;tuned large pretrained language models. We demonstrate that the order in which the samples are provided can make the difference between near state45;of45;the45;art and random guess performance essentially some permutations are fantastic and some not. We analyse this phenomenon in detail establishing that it is present across model sizes (even for the largest current models) it is not related to a specific subset of samples and that a given good permutation for one model is not transferable to another. While one could use a development set to determine which permutations are performant this would deviate from the true few45;shot setting as it requires additional annotated data. Instead we use the generative nature of language models to construct an artificial development set and based on entropy statistics of the candidate permutations on this set we identify performant prompts. Our method yields a 1337; relative improvement for GPT45;family models across eleven different established text classification tasks.
