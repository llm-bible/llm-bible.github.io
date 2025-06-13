---
layout: publication
title: 'Dehallucinating Parallel Context Extension For Retrieval-augmented Generation'
authors: Zexiong Ma, Shengnan An, Zeqi Lin, Yanzhen Zou, Jian-guang Lou, Bing Xie
conference: "Arxiv"
year: 2024
bibkey: ma2024dehallucinating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14905"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Large language models (LLMs) are susceptible to generating hallucinated
information, despite the integration of retrieval-augmented generation (RAG).
Parallel context extension (PCE) is a line of research attempting to
effectively integrating parallel (unordered) contexts, while it still suffers
from hallucinations when adapted to RAG scenarios. In this paper, we propose
DePaC (Dehallucinating Parallel Context Extension), which alleviates the
hallucination problem with context-aware negative training and
information-calibrated aggregation. DePaC is designed to alleviate two types of
in-context hallucination: fact fabrication (i.e., LLMs present claims that are
not supported by the contexts) and fact omission (i.e., LLMs fail to present
claims that can be supported by the contexts). Specifically, (1) for fact
fabrication, we apply the context-aware negative training that fine-tunes the
LLMs with negative supervisions, thus explicitly guiding the LLMs to refuse to
answer when contexts are not related to questions; (2) for fact omission, we
propose the information-calibrated aggregation which prioritizes context
windows with higher information increment from their contexts. The experimental
results on nine RAG tasks demonstrate that DePaC significantly alleviates the
two types of hallucination and consistently achieves better performances on
these tasks.
