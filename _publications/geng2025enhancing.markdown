---
layout: publication
title: 'Enhancing RAG With Active Learning On Conversation Records: Reject Incapables And Answer Capables'
authors: Xuzhao Geng, Haozhao Wang, Jun Wang, Wei Liu, Ruixuan Li
conference: "Arxiv"
year: 2025
bibkey: geng2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09073'}
tags: ['RAG', 'Training Techniques']
---
Retrieval-augmented generation (RAG) is a key technique for leveraging
external knowledge and reducing hallucinations in large language models (LLMs).
However, RAG still struggles to fully prevent hallucinated responses. To
address this, it is essential to identify samples prone to hallucination or
guide LLMs toward correct responses, which experts then annotate to develop
high-quality datasets for refining LLMs. However, the growing scarcity of such
datasets makes their creation challenging. This paper proposes using the vast
amount of conversations from widespread LLM usage to build these datasets,
training LLMs to avoid hallucination-prone questions while accurately
responding to manageable ones. Given the impracticality of expert-annotating
all conversation records, the paper introduces AL4RAG, which uses active
learning to select the most suitable conversation samples for annotation,
optimizing performance within an annotation budget. Additionally, recognizing
that traditional active learning methods are not fully compatible with RAG due
to unsuitable distance metrics, we develop a novel sample distance measurement
for RAG active learning. Extensive experiments show that our method
consistently outperforms baselines across multiple metrics.
