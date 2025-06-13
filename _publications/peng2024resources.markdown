---
layout: publication
title: 'ELOQ: Resources For Enhancing LLM Detection Of Out-of-scope Questions'
authors: Zhiyuan Peng, Jinming Nian, Alexandre Evfimievski, Yi Fang
conference: "Arxiv"
year: 2024
bibkey: peng2024resources
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14567"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) has become integral to large language
models (LLMs), particularly for conversational AI systems where user questions
may reference knowledge beyond the LLMs' training cutoff. However, many natural
user questions lack well-defined answers, either due to limited domain
knowledge or because the retrieval system returns documents that are relevant
in appearance but uninformative in content. In such cases, LLMs often produce
hallucinated answers without flagging them. While recent work has largely
focused on questions with false premises, we study out-of-scope questions,
where the retrieved document appears semantically similar to the question but
lacks the necessary information to answer it. In this paper, we propose a
guided hallucination-based approach ELOQ to automatically generate a diverse
set of out-of-scope questions from post-cutoff documents, followed by human
verification to ensure quality. We use this dataset to evaluate several LLMs on
their ability to detect out-of-scope questions and generate appropriate
responses. Finally, we introduce an improved detection method that enhances the
reliability of LLM-based question-answering systems in handling out-of-scope
questions.
