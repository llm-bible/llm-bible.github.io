---
layout: publication
title: 'Retrieval-augmented Generation To Improve Math Question-answering: Trade-offs Between Groundedness And Human Preference'
authors: Zachary Levonian, Chenglu Li, Wangda Zhu, Anoushka Gade, Owen Henkel, Millie-ellen Postle, Wanli Xing
conference: "Arxiv"
year: 2023
bibkey: levonian2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03184"}
tags: ['RAG', 'Survey Paper', 'Prompting', 'Reinforcement Learning']
---
For middle-school math students, interactive question-answering (QA) with
tutors is an effective way to learn. The flexibility and emergent capabilities
of generative large language models (LLMs) has led to a surge of interest in
automating portions of the tutoring process - including interactive QA to
support conceptual discussion of mathematical concepts. However, LLM responses
to math questions can be incorrect or mismatched to the educational context -
such as being misaligned with a school's curriculum. One potential solution is
retrieval-augmented generation (RAG), which involves incorporating a vetted
external knowledge source in the LLM prompt to increase response quality. In
this paper, we designed prompts that retrieve and use content from a
high-quality open-source math textbook to generate responses to real student
questions. We evaluate the efficacy of this RAG system for middle-school
algebra and geometry QA by administering a multi-condition survey, finding that
humans prefer responses generated using RAG, but not when responses are too
grounded in the textbook content. We argue that while RAG is able to improve
response quality, designers of math QA systems must consider trade-offs between
generating responses preferred by students and responses closely matched to
specific educational resources.
