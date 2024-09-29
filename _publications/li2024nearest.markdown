---
layout: publication
title: Nearest Neighbor Speculative Decoding For LLM Generation And Attribution
authors: Li Minghan, Chen Xilun, Holtzman Ari, Chen Beidi, Lin Jimmy, Yih Wen-tau, Lin Xi Victoria
conference: "Arxiv"
year: 2024
bibkey: li2024nearest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19325"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) often hallucinate and lack the ability to provide attribution for their generations. Semi45;parametric LMs such as kNN45;LM approach these limitations by refining the output of an LM for a given prompt using its nearest neighbor matches in a non45;parametric data store. However these models often exhibit slow inference speeds and produce non45;fluent texts. In this paper we introduce Nearest Neighbor Speculative Decoding (NEST) a novel semi45;parametric language modeling approach that is capable of incorporating real45;world text spans of arbitrary length into the LM generations and providing attribution to their sources. NEST performs token45;level retrieval at each inference step to compute a semi45;parametric mixture distribution and identify promising span continuations in a corpus. It then uses an approximate speculative decoding procedure that accepts a prefix of the retrieved span or generates a new token. NEST significantly enhances the generation quality and attribution rate of the base LM across a variety of knowledge45;intensive tasks surpassing the conventional kNN45;LM method and performing competitively with in45;context retrieval augmentation. In addition NEST substantially improves the generation speed achieving a 1.8x speedup in inference time when applied to Llama45;245;Chat 70B.
