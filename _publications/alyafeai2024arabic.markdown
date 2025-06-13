---
layout: publication
title: 'Arabic Stable LM: Adapting Stable LM 2 1.6B To Arabic'
authors: Zaid Alyafeai, Michael Pieler, Hannah Teufel, Jonathan Tow, Marco Bellagente, Duy Phung, Nikhil Pinnaparaju, Reshinth Adithyan, Paulo Rocha, Maksym Zhuravinskyi, Carlos Riquelme
conference: "Arxiv"
year: 2024
bibkey: alyafeai2024arabic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04277"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Large Language Models (LLMs) have shown impressive results in multiple
domains of natural language processing (NLP) but are mainly focused on the
English language. Recently, more LLMs have incorporated a larger proportion of
multilingual text to represent low-resource languages. In Arabic NLP, several
Arabic-centric LLMs have shown remarkable results on multiple benchmarks in the
past two years. However, most Arabic LLMs have more than 7 billion parameters,
which increases their hardware requirements and inference latency, when
compared to smaller LLMs. This paper introduces Arabic Stable LM 1.6B in a base
and chat version as a small but powerful Arabic-centric LLM. Our Arabic Stable
LM 1.6B chat model achieves impressive results on several benchmarks beating
multiple models with up to 8x the parameters. In addition, we show the benefit
of mixing in synthetic instruction tuning data by augmenting our fine-tuning
data with a large synthetic dialogue dataset.
