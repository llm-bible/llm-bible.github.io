---
layout: publication
title: 'Using Pretrained Large Language Model With Prompt Engineering To Answer Biomedical Questions'
authors: Zhou Wenxin, Ngo Thuy Hang
conference: "Arxiv"
year: 2024
bibkey: zhou2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06779"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting']
---
Our team participated in the BioASQ 2024 Task12b and Synergy tasks to build a
system that can answer biomedical questions by retrieving relevant articles and
snippets from the PubMed database and generating exact and ideal answers. We
propose a two-level information retrieval and question-answering system based
on pre-trained large language models (LLM), focused on LLM prompt engineering
and response post-processing. We construct prompts with in-context few-shot
examples and utilize post-processing techniques like resampling and malformed
response detection. We compare the performance of various pre-trained LLM
models on this challenge, including Mixtral, OpenAI GPT and Llama2. Our
best-performing system achieved 0.14 MAP score on document retrieval, 0.05 MAP
score on snippet retrieval, 0.96 F1 score for yes/no questions, 0.38 MRR score
for factoid questions and 0.50 F1 score for list questions in Task 12b.
