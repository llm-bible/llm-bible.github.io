---
layout: publication
title: 'An Exam-based Evaluation Approach Beyond Traditional Relevance Judgments'
authors: Naghmeh Farzi, Laura Dietz
conference: "Arxiv"
year: 2024
bibkey: farzi2024exam
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.00309'}
tags: ['Reinforcement Learning', 'Applications']
---
Current IR evaluation is based on relevance judgments, created either
manually or automatically, with decisions outsourced to Large Language Models
(LLMs). We offer an alternative paradigm, that never relies on relevance
judgments in any form. Instead, a text is defined as relevant if it contains
information that enables the answering of key questions. We use this idea to
design the EXAM Answerability Metric to evaluate information
retrieval/generation systems for their ability to provide topically relevant
information.
  We envision the role of a human judge to edit and define an exam question
bank that will test for the presence of relevant information in text. We
support this step by generating an initial set of exam questions. In the next
phase, an LLM-based question answering system will automatically grade system
responses by tracking which exam questions are answerable with which system
responses. We propose two evaluation measures, the recall-oriented EXAM Cover
metric, and the precision-oriented EXAM Qrels metric, the latter which can be
implemented with trec_eval. This paradigm not only allows for the expansion of
the exam question set post-hoc but also facilitates the ongoing evaluation of
future information systems, whether they focus on retrieval, generation, or
both.
