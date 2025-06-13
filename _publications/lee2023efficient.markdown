---
layout: publication
title: 'Orchestrallm: Efficient Orchestration Of Language Models For Dialogue State Tracking'
authors: Chia-hsuan Lee, Hao Cheng, Mari Ostendorf
conference: "Arxiv"
year: 2023
bibkey: lee2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09758"}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
Large language models (LLMs) have revolutionized the landscape of Natural
Language Processing systems, but are computationally expensive. To reduce the
cost without sacrificing performance, previous studies have explored various
approaches to harness the potential of Small Language Models (SLMs) as
cost-effective alternatives to their larger counterparts. Driven by findings
that SLMs and LLMs exhibit complementary strengths in a structured knowledge
extraction task, this work presents a novel SLM/LLM routing framework designed
to improve computational efficiency and enhance task performance. First,
exemplar pools are created to represent the types of contexts where each LM
provides a more reliable answer, leveraging a sentence embedding fine-tuned so
that context similarity is close to dialogue state similarity. Then, during
inference, the k-nearest exemplars to the testing instance are retrieved, and
the instance is routed according to majority vote. In dialogue state tracking
tasks, the proposed routing framework enhances performance substantially
compared to relying solely on LLMs, while reducing the computational costs by
over 50%.
