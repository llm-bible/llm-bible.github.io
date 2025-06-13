---
layout: publication
title: 'How Do You Know That? Teaching Generative Language Models To Reference Answers To Biomedical Questions'
authors: Bojana Bašaragin, Adela Ljajić, Darija Medvecki, Lorenzo Cassano, Miloš Košprdić, Nikola Milošević
conference: "Arxiv"
year: 2024
bibkey: bašaragin2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05015"}
tags: ['Prompting', 'RAG', 'Model Architecture', 'GPT']
---
Large language models (LLMs) have recently become the leading source of
answers for users' questions online. Despite their ability to offer eloquent
answers, their accuracy and reliability can pose a significant challenge. This
is especially true for sensitive domains such as biomedicine, where there is a
higher need for factually correct answers. This paper introduces a biomedical
retrieval-augmented generation (RAG) system designed to enhance the reliability
of generated responses. The system is based on a fine-tuned LLM for the
referenced question-answering, where retrieved relevant abstracts from PubMed
are passed to LLM's context as input through a prompt. Its output is an answer
based on PubMed abstracts, where each statement is referenced accordingly,
allowing the users to verify the answer. Our retrieval system achieves an
absolute improvement of 23% compared to the PubMed search engine. Based on the
manual evaluation on a small sample, our fine-tuned LLM component achieves
comparable results to GPT-4 Turbo in referencing relevant abstracts. We make
the dataset used to fine-tune the models and the fine-tuned models based on
Mistral-7B-instruct-v0.1 and v0.2 publicly available.
