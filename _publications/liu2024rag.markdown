---
layout: publication
title: 'Rag-instruct: Boosting Llms With Diverse Retrieval-augmented Instructions'
authors: Wanlong Liu, Junying Chen, Ke Ji, Li Zhou, Wenyu Chen, Benyou Wang
conference: "Arxiv"
year: 2024
bibkey: liu2024rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.00353'}
  - {name: "Code", url: 'https://github.com/FreedomIntelligence/RAG-Instruct'}
tags: ['RAG', 'Has Code']
---
Retrieval-Augmented Generation (RAG) has emerged as a key paradigm for
enhancing large language models (LLMs) by incorporating external knowledge.
However, current RAG methods face two limitations: (1) they only cover limited
RAG scenarios. (2) They suffer from limited task diversity due to the lack of a
general RAG dataset. To address these limitations, we propose RAG-Instruct, a
general method for synthesizing diverse and high-quality RAG instruction data
based on any source corpus. Our approach leverages (1) five RAG paradigms,
which encompass diverse query-document relationships, and (2) instruction
simulation, which enhances instruction diversity and quality by utilizing the
strengths of existing instruction datasets. Using this method, we construct a
40K instruction dataset from Wikipedia, comprehensively covering diverse RAG
scenarios and tasks. Experiments demonstrate that RAG-Instruct effectively
enhances LLMs' RAG capabilities, achieving strong zero-shot performance and
significantly outperforming various RAG baselines across a diverse set of
tasks. RAG-Instruct is publicly available at
https://github.com/FreedomIntelligence/RAG-Instruct.
