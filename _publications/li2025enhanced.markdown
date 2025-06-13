---
layout: publication
title: 'Enhanced Retrieval Of Long Documents: Leveraging Fine-grained Block Representations With Large Language Models'
authors: Minghan Li, Eric Gaussier, Guodong Zhou
conference: "Arxiv"
year: 2025
bibkey: li2025enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17039"}
tags: ['RAG', 'Tools', 'Applications']
---
In recent years, large language models (LLMs) have demonstrated exceptional
power in various domains, including information retrieval. Most of the previous
practices involve leveraging these models to create a single embedding for each
query, each passage, or each document individually, a strategy exemplified and
used by the Retrieval-Augmented Generation (RAG) framework. While this method
has proven effective, we argue that it falls short in fully capturing the
nuanced intricacies of document-level texts due to its reliance on a relatively
coarse-grained representation. To address this limitation, we introduce a
novel, fine-grained approach aimed at enhancing the accuracy of relevance
scoring for long documents. Our methodology firstly segments a long document
into blocks, each of which is embedded using an LLM, for matching with the
query representation. When calculating the relevance score, we aggregate the
query-block relevance scores through a weighted sum method, yielding a
comprehensive score for the query with the entire document. Despite its
apparent simplicity, our experimental findings reveal that this approach
outperforms standard representation methods and achieves a significant
reduction in embedding generation latency. Moreover, by carefully optimizing
pairwise loss functions, superior performances have been achieved.
