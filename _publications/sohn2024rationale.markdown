---
layout: publication
title: 'Rationale-guided Retrieval Augmented Generation For Medical Question Answering'
authors: Jiwoong Sohn, Yein Park, Chanwoong Yoon, Sihyeon Park, Hyeon Hwang, Mujeen Sung, Hyunjae Kim, Jaewoo Kang
conference: "Arxiv"
year: 2024
bibkey: sohn2024rationale
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00300'}
  - {name: "Code", url: 'https://github.com/dmis-lab/RAG2'}
tags: ['Has Code', 'RAG', 'Applications', 'Tools', 'Ethics and Bias']
---
Large language models (LLM) hold significant potential for applications in
biomedicine, but they struggle with hallucinations and outdated knowledge.
While retrieval-augmented generation (RAG) is generally employed to address
these issues, it also has its own set of challenges: (1) LLMs are vulnerable to
irrelevant or incorrect context, (2) medical queries are often not
well-targeted for helpful information, and (3) retrievers are prone to bias
toward the specific source corpus they were trained on. In this study, we
present RAG\\(^2\\) (RAtionale-Guided RAG), a new framework for enhancing the
reliability of RAG in biomedical contexts. RAG\\(^2\\) incorporates three key
innovations: a small filtering model trained on perplexity-based labels of
rationales, which selectively augments informative snippets of documents while
filtering out distractors; LLM-generated rationales as queries to improve the
utility of retrieved snippets; a structure designed to retrieve snippets evenly
from a comprehensive set of four biomedical corpora, effectively mitigating
retriever bias. Our experiments demonstrate that RAG\\(^2\\) improves the
state-of-the-art LLMs of varying sizes, with improvements of up to 6.1%, and
it outperforms the previous best medical RAG model by up to 5.6% across three
medical question-answering benchmarks. Our code is available at
https://github.com/dmis-lab/RAG2.
