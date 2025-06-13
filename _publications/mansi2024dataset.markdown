---
layout: publication
title: 'Amalrec: A Dataset For Relation Extraction And Classification Leveraging Amalgamation Of Large Language Models'
authors: Mansi, Pranshu Pandya, Mahek Bhavesh Vora, Soumya Bharadwaj, Ashish Anand
conference: "Arxiv"
year: 2024
bibkey: mansi2024dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20427"}
tags: ['Ethics and Bias', 'LREC', 'RAG', 'Tools']
---
Existing datasets for relation classification and extraction often exhibit
limitations such as restricted relation types and domain-specific biases. This
work presents a generic framework to generate well-structured sentences from
given tuples with the help of Large Language Models (LLMs). This study has
focused on the following major questions: (i) how to generate sentences from
relation tuples, (ii) how to compare and rank them, (iii) can we combine
strengths of individual methods and amalgamate them to generate an even bette
quality of sentences, and (iv) how to evaluate the final dataset? For the first
question, we employ a multifaceted 5-stage pipeline approach, leveraging LLMs
in conjunction with template-guided generation. We introduce Sentence
Evaluation Index(SEI) that prioritizes factors like grammatical correctness,
fluency, human-aligned sentiment, accuracy, and complexity to answer the first
part of the second question. To answer the second part of the second question,
this work introduces a SEI-Ranker module that leverages SEI to select top
candidate generations. The top sentences are then strategically amalgamated to
produce the final, high-quality sentence. Finally, we evaluate our dataset on
LLM-based and SOTA baselines for relation classification. The proposed dataset
features 255 relation types, with 15K sentences in the test set and around 150k
in the train set organized in, significantly enhancing relational diversity and
complexity. This work not only presents a new comprehensive benchmark dataset
for RE/RC task, but also compare different LLMs for generation of quality
sentences from relational tuples.
