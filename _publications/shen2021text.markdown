---
layout: publication
title: 'Text Is NOT Enough: Integrating Visual Impressions Into Open-domain Dialogue Generation'
authors: Lei Shen, Haolan Zhan, Xin Shen, Yonghao Song, Xiaofang Zhao
conference: "Arxiv"
year: 2021
bibkey: shen2021text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2109.05778'}
tags: ['Attention Mechanism', 'Tools', 'Model Architecture']
---
Open-domain dialogue generation in natural language processing (NLP) is by
default a pure-language task, which aims to satisfy human need for daily
communication on open-ended topics by producing related and informative
responses. In this paper, we point out that hidden images, named as visual
impressions (VIs), can be explored from the text-only data to enhance dialogue
understanding and help generate better responses. Besides, the semantic
dependency between an dialogue post and its response is complicated, e.g., few
word alignments and some topic transitions. Therefore, the visual impressions
of them are not shared, and it is more reasonable to integrate the response
visual impressions (RVIs) into the decoder, rather than the post visual
impressions (PVIs). However, both the response and its RVIs are not given
directly in the test process. To handle the above issues, we propose a
framework to explicitly construct VIs based on pure-language dialogue datasets
and utilize them for better dialogue understanding and generation.
Specifically, we obtain a group of images (PVIs) for each post based on a
pre-trained word-image mapping model. These PVIs are used in a co-attention
encoder to get a post representation with both visual and textual information.
Since the RVIs are not provided directly during testing, we design a cascade
decoder that consists of two sub-decoders. The first sub-decoder predicts the
content words in response, and applies the word-image mapping model to get
those RVIs. Then, the second sub-decoder generates the response based on the
post and RVIs. Experimental results on two open-domain dialogue datasets show
that our proposed approach achieves superior performance over competitive
baselines.
