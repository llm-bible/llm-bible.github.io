---
layout: publication
title: Byte Pair Encoding Is Suboptimal For Language Model Pretraining
authors: Kaj Bostrom, Greg Durrett
conference: Arxiv
year: 2020
citations: 51
bibkey: bostrom2020byte
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.03720'}]
tags: [Tokenization, Pre-Training, Transformer, Language Modeling, Masked Language
    Model, BERT]
---
The success of pretrained transformer language models (LMs) in natural
language processing has led to a wide range of pretraining setups. In
particular, these models employ a variety of subword tokenization methods, most
notably byte-pair encoding (BPE) (Sennrich et al., 2016; Gage, 1994), the
WordPiece method (Schuster and Nakajima, 2012), and unigram language modeling
(Kudo, 2018), to segment text. However, to the best of our knowledge, the
literature does not contain a direct evaluation of the impact of tokenization
on language model pretraining. We analyze differences between BPE and unigram
LM tokenization, finding that the latter method recovers subword units that
align more closely with morphology and avoids problems stemming from BPE's
greedy construction procedure. We then compare the fine-tuned task performance
of identical transformer masked language models pretrained with these
tokenizations. Across downstream tasks and two languages (English and
Japanese), we find that the unigram LM tokenization method matches or
outperforms BPE. We hope that developers of future pretrained LMs will consider
adopting the unigram LM method over the more prevalent BPE.