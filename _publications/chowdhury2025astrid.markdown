---
layout: publication
title: 'ASTRID -- An Automated And Scalable Triad For The Evaluation Of Rag-based Clinical Question Answering Systems'
authors: Mohita Chowdhury, Yajie Vera He, Aisling Higham, Ernest Lim
conference: "Arxiv"
year: 2025
bibkey: chowdhury2025astrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08208"}
tags: ['Agentic', 'Applications', 'RAG', 'Merging', 'Reinforcement Learning', 'Prompting']
---
Large Language Models (LLMs) have shown impressive potential in clinical
question answering (QA), with Retrieval Augmented Generation (RAG) emerging as
a leading approach for ensuring the factual accuracy of model responses.
However, current automated RAG metrics perform poorly in clinical and
conversational use cases. Using clinical human evaluations of responses is
expensive, unscalable, and not conducive to the continuous iterative
development of RAG systems. To address these challenges, we introduce ASTRID -
an Automated and Scalable TRIaD for evaluating clinical QA systems leveraging
RAG - consisting of three metrics: Context Relevance (CR), Refusal Accuracy
(RA), and Conversational Faithfulness (CF). Our novel evaluation metric, CF, is
designed to better capture the faithfulness of a model's response to the
knowledge base without penalising conversational elements. To validate our
triad, we curate a dataset of over 200 real-world patient questions posed to an
LLM-based QA agent during surgical follow-up for cataract surgery - the highest
volume operation in the world - augmented with clinician-selected questions for
emergency, clinical, and non-clinical out-of-domain scenarios. We demonstrate
that CF can predict human ratings of faithfulness better than existing
definitions for conversational use cases. Furthermore, we show that evaluation
using our triad consisting of CF, RA, and CR exhibits alignment with clinician
assessment for inappropriate, harmful, or unhelpful responses. Finally, using
nine different LLMs, we demonstrate that the three metrics can closely agree
with human evaluations, highlighting the potential of these metrics for use in
LLM-driven automated evaluation pipelines. We also publish the prompts and
datasets for these experiments, providing valuable resources for further
research and development.
