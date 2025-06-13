---
layout: publication
title: 'Learning To Refine Source Representations For Neural Machine Translation'
authors: Xinwei Geng, Longyue Wang, Xing Wang, Bing Qin, Ting Liu, Zhaopeng Tu
conference: "Arxiv"
year: 2018
bibkey: geng2018learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1812.10230"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
Neural machine translation (NMT) models generally adopt an encoder-decoder
architecture for modeling the entire translation process. The encoder
summarizes the representation of input sentence from scratch, which is
potentially a problem if the sentence is ambiguous. When translating a text,
humans often create an initial understanding of the source sentence and then
incrementally refine it along the translation on the target side. Starting from
this intuition, we propose a novel encoder-refiner-decoder framework, which
dynamically refines the source representations based on the generated
target-side information at each decoding step. Since the refining operations
are time-consuming, we propose a strategy, leveraging the power of
reinforcement learning models, to decide when to refine at specific decoding
steps. Experimental results on both Chinese-English and English-German
translation tasks show that the proposed approach significantly and
consistently improves translation performance over the standard encoder-decoder
framework. Furthermore, when refining strategy is applied, results still show
reasonable improvement over the baseline without much decrease in decoding
speed.
