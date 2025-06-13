---
layout: publication
title: 'EVOR: Evolving Retrieval For Code Generation'
authors: Hongjin Su, Shuyang Jiang, Yuhang Lai, Haoyuan Wu, Boao Shi, Che Liu, Qian Liu, Tao Yu
conference: "Arxiv"
year: 2024
bibkey: su2024evolving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.12317'}
  - {name: "Code", url: 'https://arks-codegen.github.io'}
tags: ['RAG', 'Has Code', 'Prompting', 'Applications']
---
Recently the retrieval-augmented generation (RAG) has been successfully
applied in code generation. However, existing pipelines for retrieval-augmented
code generation (RACG) employ static knowledge bases with a single source,
limiting the adaptation capabilities of Large Language Models (LLMs) to domains
they have insufficient knowledge of. In this work, we develop a novel pipeline,
EVOR, that employs the synchronous evolution of both queries and diverse
knowledge bases. On two realistic settings where the external knowledge is
required to solve code generation tasks, we compile four new datasets
associated with frequently updated libraries and long-tail programming
languages, named EVOR-BENCH. Extensive experiments demonstrate that EVOR
achieves two to four times of execution accuracy compared to other methods such
as Reflexion (Shinn et al., 2024), DocPrompting (Zhou et al., 2023), etc. We
demonstrate that EVOR is flexible and can be easily combined with them to
achieve further improvement. Further analysis reveals that EVOR benefits from
the synchronous evolution of queries and documents and the diverse information
sources in the knowledge base. We hope that our studies will inspire more
insights into the design of advanced RACG pipelines in future research. Our
model, code, and data are available at https://arks-codegen.github.io.
