---
layout: publication
title: 'On The Adaptation Of Unlimiformer For Decoder-only Transformers'
authors: Kian Ahrabian, Alon Benhaim, Barun Patra, Jay Pujara, Saksham Singhal, Xia Song
conference: "Arxiv"
year: 2024
bibkey: ahrabian2024adaptation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.01637'}
tags: ['Attention Mechanism', 'Transformer', 'GPT', 'BERT', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
One of the prominent issues stifling the current generation of large language
models is their limited context length. Recent proprietary models such as GPT-4
and Claude 2 have introduced longer context lengths, 8k/32k and 100k,
respectively; however, despite the efforts in the community, most common
models, such as LLama-2, have a context length of 4k or less. Unlimiformer
(Bertsch et al., 2023) is a recently popular vector-retrieval augmentation
method that offloads cross-attention computations to a kNN index. However, its
main limitation is incompatibility with decoder-only transformers out of the
box. In this work, we explore practical considerations of adapting Unlimiformer
to decoder-only transformers and introduce a series of modifications to
overcome this limitation. Moreover, we expand the original experimental setup
on summarization to include a new task (i.e., free-form Q&A) and an
instruction-tuned model (i.e., a custom 6.7B GPT model). Our results showcase
the effectiveness of these modifications on summarization, performing on par
with a model with 2x the context length. Moreover, we discuss limitations and
future directions for free-form Q&A and instruction-tuned models.
