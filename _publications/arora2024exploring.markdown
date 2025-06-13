---
layout: publication
title: 'Calmqa: Exploring Culturally Specific Long-form Question Answering Across 23 Languages'
authors: Shane Arora, Marzena Karpinska, Hung-ting Chen, Ipsita Bhattacharjee, Mohit Iyyer, Eunsol Choi
conference: "Arxiv"
year: 2024
bibkey: arora2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17761"}
tags: ['RAG', 'Applications', 'Tools']
---
Large language models (LLMs) are used for long-form question answering
(LFQA), which requires them to generate paragraph-length answers to complex
questions. While LFQA has been well-studied in English, this research has not
been extended to other languages. To bridge this gap, we introduce CaLMQA, a
collection of 1.5K complex culturally specific questions spanning 23 languages
and 51 culturally agnostic questions translated from English into 22 other
languages. We define culturally specific questions as those uniquely or more
likely to be asked by people from cultures associated with the question's
language. We collect naturally-occurring questions from community web forums
and hire native speakers to write questions to cover under-resourced,
rarely-studied languages such as Fijian and Kirundi. Our dataset contains
diverse, complex questions that reflect cultural topics (e.g. traditions, laws,
news) and the language usage of native speakers. We automatically evaluate a
suite of open- and closed-source models on CaLMQA by detecting incorrect
language and token repetitions in answers, and observe that the quality of
LLM-generated answers degrades significantly for some low-resource languages.
Lastly, we perform human evaluation on a subset of models and languages. Manual
evaluation reveals that model performance is significantly worse for culturally
specific questions than for culturally agnostic questions. Our findings
highlight the need for further research in non-English LFQA and provide an
evaluation framework.
