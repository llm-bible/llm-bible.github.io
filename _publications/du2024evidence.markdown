---
layout: publication
title: 'Evidence-enhanced Triplet Generation Framework For Hallucination Alleviation In Generative Question Answering'
authors: Du Haowei, Zhang Huishuai, Zhao Dongyan
conference: "Arxiv"
year: 2024
bibkey: du2024evidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15037"}
tags: ['Applications', 'RAG', 'Tools']
---
To address the hallucination in generative question answering (GQA) where the
answer can not be derived from the document, we propose a novel
evidence-enhanced triplet generation framework, EATQA, encouraging the model to
predict all the combinations of (Question, Evidence, Answer) triplet by
flipping the source pair and the target label to understand their logical
relationships, i.e., predict Answer(A), Question(Q), and Evidence(E) given a
QE, EA, and QA pairs, respectively. Furthermore, we bridge the distribution gap
to distill the knowledge from evidence in inference stage. Our framework
ensures the model to learn the logical relation between query, evidence and
answer, which simultaneously improves the evidence generation and query
answering. In this paper, we apply EATQA to LLama and it outperforms other
LLMs-based methods and hallucination mitigation approaches on two challenging
GQA benchmarks. Further analysis shows that our method not only keeps prior
knowledge within LLM, but also mitigates hallucination and generates faithful
answers.
