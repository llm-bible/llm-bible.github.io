---
layout: publication
title: 'Long-span Language Modeling For Speech Recognition'
authors: Sarangarajan Parthasarathy, William Gale, Xie Chen, George Polovets, Shuangyu Chang
conference: "Arxiv"
year: 2019
bibkey: parthasarathy2019long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.04571"}
tags: ['Transformer', 'INTERSPEECH', 'RAG', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
We explore neural language modeling for speech recognition where the context
spans multiple sentences. Rather than encode history beyond the current
sentence using a cache of words or document-level features, we focus our study
on the ability of LSTM and Transformer language models to implicitly learn to
carry over context across sentence boundaries. We introduce a new architecture
that incorporates an attention mechanism into LSTM to combine the benefits of
recurrent and attention architectures. We conduct language modeling and speech
recognition experiments on the publicly available LibriSpeech corpus. We show
that conventional training on a paragraph-level corpus results in significant
reductions in perplexity compared to training on a sentence-level corpus. We
also describe speech recognition experiments using long-span language models in
second-pass re-ranking, and provide insights into the ability of such models to
take advantage of context beyond the current sentence.
