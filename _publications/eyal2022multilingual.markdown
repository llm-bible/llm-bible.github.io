---
layout: publication
title: 'Multilingual Sequence-to-sequence Models For Hebrew NLP'
authors: Matan Eyal, Hila Noga, Roee Aharoni, Idan Szpektor, Reut Tsarfaty
conference: "Arxiv"
year: 2022
bibkey: eyal2022multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09682"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Recent work attributes progress in NLP to large language models (LMs) with
increased model size and large quantities of pretraining data. Despite this,
current state-of-the-art LMs for Hebrew are both under-parameterized and
under-trained compared to LMs in other languages. Additionally, previous work
on pretrained Hebrew LMs focused on encoder-only models. While the encoder-only
architecture is beneficial for classification tasks, it does not cater well for
sub-word prediction tasks, such as Named Entity Recognition, when considering
the morphologically rich nature of Hebrew. In this paper we argue that
sequence-to-sequence generative architectures are more suitable for LLMs in the
case of morphologically rich languages (MRLs) such as Hebrew. We demonstrate
that by casting tasks in the Hebrew NLP pipeline as text-to-text tasks, we can
leverage powerful multilingual, pretrained sequence-to-sequence models as mT5,
eliminating the need for a specialized, morpheme-based, separately fine-tuned
decoder. Using this approach, our experiments show substantial improvements
over previously published results on existing Hebrew NLP benchmarks. These
results suggest that multilingual sequence-to-sequence models present a
promising building block for NLP for MRLs.
