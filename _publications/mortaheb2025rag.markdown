---
layout: publication
title: 'Rag-check: Evaluating Multimodal Retrieval Augmented Generation Performance'
authors: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus
conference: "Arxiv"
year: 2025
bibkey: mortaheb2025rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.03995'}
tags: ['RAG', 'Model Architecture', 'Tools', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) improves large language models (LLMs) by
using external knowledge to guide response generation, reducing hallucinations.
However, RAG, particularly multi-modal RAG, can introduce new hallucination
sources: (i) the retrieval process may select irrelevant pieces (e.g.,
documents, images) as raw context from the database, and (ii) retrieved images
are processed into text-based context via vision-language models (VLMs) or
directly used by multi-modal language models (MLLMs) like GPT-4o, which may
hallucinate. To address this, we propose a novel framework to evaluate the
reliability of multi-modal RAG using two performance measures: (i) the
relevancy score (RS), assessing the relevance of retrieved entries to the
query, and (ii) the correctness score (CS), evaluating the accuracy of the
generated response. We train RS and CS models using a ChatGPT-derived database
and human evaluator samples. Results show that both models achieve ~88%
accuracy on test data. Additionally, we construct a 5000-sample human-annotated
database evaluating the relevancy of retrieved pieces and the correctness of
response statements. Our RS model aligns with human preferences 20% more often
than CLIP in retrieval, and our CS model matches human preferences ~91% of the
time. Finally, we assess various RAG systems' selection and generation
performances using RS and CS.
