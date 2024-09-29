---
layout: publication
title: Xc45;cache Cross45;attending To Cached Context For Efficient LLM Inference
authors: Monteiro João, Marcotte Étienne, Noël Pierre-andré, Zantedeschi Valentina, Vázquez David, Chapados Nicolas, Pal Christopher, Taslakian Perouz
conference: "Arxiv"
year: 2024
bibkey: monteiro2024xc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15420"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
In45;context learning (ICL) approaches typically leverage prompting to condition decoder45;only language model generation on reference information. Just45;in45;time processing of a context is inefficient due to the quadratic cost of self45;attention operations and caching is desirable. However caching transformer states can easily require almost as much space as the model parameters. When the right context isnt known in advance caching ICL can be challenging. This work addresses these limitations by introducing models that inspired by the encoder45;decoder architecture use cross45;attention to condition generation on reference text without the prompt. More precisely we leverage pre45;trained decoder45;only models and only train a small number of added layers. We use Question45;Answering (QA) as a testbed to evaluate the ability of our models to perform conditional generation and observe that they outperform ICL are comparable to fine45;tuned prompted LLMs and drastically reduce the space footprint relative to standard KV caching by two orders of magnitude.
