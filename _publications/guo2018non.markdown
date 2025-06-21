---
layout: publication
title: Non-autoregressive Neural Machine Translation With Enhanced Decoder Input
authors: Junliang Guo et al.
conference: Arxiv
year: 2018
citations: 33
bibkey: guo2018non
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.09664'}]
tags: []
---
Non-autoregressive translation (NAT) models, which remove the dependence on
previous target tokens from the inputs of the decoder, achieve significantly
inference speedup but at the cost of inferior accuracy compared to
autoregressive translation (AT) models. Previous work shows that the quality of
the inputs of the decoder is important and largely impacts the model accuracy.
In this paper, we propose two methods to enhance the decoder inputs so as to
improve NAT models. The first one directly leverages a phrase table generated
by conventional SMT approaches to translate source tokens to target tokens,
which are then fed into the decoder as inputs. The second one transforms
source-side word embeddings to target-side word embeddings through
sentence-level alignment and word-level adversary learning, and then feeds the
transformed word embeddings into the decoder as inputs. Experimental results
show our method largely outperforms the NAT baseline~\citep\{gu2017non\} by
\\(5.11\\) BLEU scores on WMT14 English-German task and \\(4.72\\) BLEU scores on WMT16
English-Romanian task.