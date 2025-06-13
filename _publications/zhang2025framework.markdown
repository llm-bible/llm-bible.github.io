---
layout: publication
title: 'SAGE: A Framework Of Precise Retrieval For RAG'
authors: Jintao Zhang, Guoliang Li, Jinyang Su
conference: "Arxiv"
year: 2025
bibkey: zhang2025framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01713"}
tags: ['RAG', 'Tools', 'Efficiency and Optimization']
---
Retrieval-augmented generation (RAG) has demonstrated significant proficiency
in conducting question-answering (QA) tasks within a specified corpus.
Nonetheless, numerous failure instances of RAG in QA still exist. These
failures are not solely attributable to the limitations of Large Language
Models (LLMs); instead, they predominantly arise from the retrieval of
inaccurate information for LLMs due to two limitations: (1) Current RAG methods
segment the corpus without considering semantics, making it difficult to find
relevant context due to impaired correlation between questions and the
segments. (2) There is a trade-off between missing essential context with fewer
context retrieved and getting irrelevant context with more context retrieved.
  In this paper, we introduce a RAG framework (SAGE), to overcome these
limitations. First, to address the segmentation issue without considering
semantics, we propose to train a semantic segmentation model. This model is
trained to segment the corpus into semantically complete chunks. Second, to
ensure that only the most relevant chunks are retrieved while the irrelevant
ones are ignored, we design a chunk selection algorithm to dynamically select
chunks based on the decreasing speed of the relevance score, leading to a more
relevant selection. Third, to further ensure the precision of the retrieved
chunks, we propose letting LLMs assess whether retrieved chunks are excessive
or lacking and then adjust the amount of context accordingly. Experiments show
that SAGE outperforms baselines by 61.25% in the quality of QA on average.
Moreover, by avoiding retrieving noisy context, SAGE lowers the cost of the
tokens consumed in LLM inference and achieves a 49.41% enhancement in cost
efficiency on average. Additionally, our work offers valuable insights for
boosting RAG.
