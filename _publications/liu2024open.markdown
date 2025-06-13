---
layout: publication
title: 'Open Domain Question Answering With Conflicting Contexts'
authors: Siyi Liu, Qiang Ning, Kishaloy Halder, Wei Xiao, Zheng Qi, Phu Mon Htut, Yi Zhang, Neha Anna John, Bonan Min, Yassine Benajiba, Dan Roth
conference: "Arxiv"
year: 2024
bibkey: liu2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12311"}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Applications']
---
Open domain question answering systems frequently rely on information
retrieved from large collections of text (such as the Web) to answer questions.
However, such collections of text often contain conflicting information, and
indiscriminately depending on this information may result in untruthful and
inaccurate answers. To understand the gravity of this problem, we collect a
human-annotated dataset, Question Answering with Conflicting Contexts (QACC),
and find that as much as 25% of unambiguous, open domain questions can lead to
conflicting contexts when retrieved using Google Search. We evaluate and
benchmark three powerful Large Language Models (LLMs) with our dataset QACC and
demonstrate their limitations in effectively addressing questions with
conflicting information. To explore how humans reason through conflicting
contexts, we request our annotators to provide explanations for their
selections of correct answers. We demonstrate that by finetuning LLMs to
explain their answers, we can introduce richer information into their training
that guide them through the process of reasoning with conflicting contexts.
