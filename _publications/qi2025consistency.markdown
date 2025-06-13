---
layout: publication
title: 'On The Consistency Of Multilingual Context Utilization In Retrieval-augmented Generation'
authors: Jirui Qi, Raquel Fernández, Arianna Bisazza
conference: "Arxiv"
year: 2025
bibkey: qi2025consistency
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00597'}
tags: ['Reinforcement Learning', 'RAG']
---
Retrieval-augmented generation (RAG) with large language models (LLMs) has
demonstrated strong performance in multilingual question-answering (QA) tasks
by leveraging relevant passages retrieved from corpora. In multilingual RAG
(mRAG), the retrieved passages can be written in languages other than that of
the query entered by the user, making it challenging for LLMs to effectively
utilize the provided information. Recent research suggests that retrieving
passages from multilingual corpora can improve RAG performance, particularly
for low-resource languages. However, the extent to which LLMs can leverage
different kinds of multilingual contexts to generate accurate answers,
*independently from retrieval quality*, remains understudied. In this paper, we
conduct an extensive assessment of LLMs' ability to (i) make consistent use of
a relevant passage regardless of its language, (ii) respond in the expected
language, and (iii) focus on the relevant passage even when multiple
`distracting' passages in different languages are provided in the context. Our
experiments with four LLMs across three QA datasets covering a total of 48
languages reveal a surprising ability of LLMs to extract the relevant
information from out-language passages, but a much weaker ability to formulate
a full answer in the correct language. Our analysis, based on both accuracy and
feature attribution techniques, further shows that distracting passages
negatively impact answer quality regardless of their language. However,
distractors in the query language exert a slightly stronger influence. Taken
together, our findings deepen the understanding of how LLMs utilize context in
mRAG systems, providing directions for future improvements.
