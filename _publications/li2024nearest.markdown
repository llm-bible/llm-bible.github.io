---
layout: publication
title: 'Nearest Neighbor Speculative Decoding For LLM Generation And Attribution'
authors: Minghan Li, Xilun Chen, Ari Holtzman, Beidi Chen, Jimmy Lin, Wen-tau Yih, Xi Victoria Lin
conference: "Advances in Neural Information Processing Systems (2024) vol. 37 page 80987-81015"
year: 2024
bibkey: li2024nearest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19325"}
  - {name: "Code", url: "https://github.com/facebookresearch/NEST/tree/main"}
tags: ['Has Code', 'Prompting', 'Language Modeling', 'Reinforcement Learning']
---
Large language models (LLMs) often hallucinate and lack the ability to
provide attribution for their generations. Semi-parametric LMs, such as kNN-LM,
approach these limitations by refining the output of an LM for a given prompt
using its nearest neighbor matches in a non-parametric data store. However,
these models often exhibit slow inference speeds and produce non-fluent texts.
In this paper, we introduce Nearest Neighbor Speculative Decoding (NEST), a
novel semi-parametric language modeling approach that is capable of
incorporating real-world text spans of arbitrary length into the LM generations
and providing attribution to their sources. NEST performs token-level retrieval
at each inference step to compute a semi-parametric mixture distribution and
identify promising span continuations in a corpus. It then uses an approximate
speculative decoding procedure that accepts a prefix of the retrieved span or
generates a new token. NEST significantly enhances the generation quality and
attribution rate of the base LM across a variety of knowledge-intensive tasks,
surpassing the conventional kNN-LM method and performing competitively with
in-context retrieval augmentation. In addition, NEST substantially improves the
generation speed, achieving a 1.8x speedup in inference time when applied to
Llama-2-Chat 70B. Code will be released at
https://github.com/facebookresearch/NEST/tree/main.
