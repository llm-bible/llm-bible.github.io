---
layout: publication
title: 'Examining Long-context Large Language Models For Environmental Review Document Comprehension'
authors: Hung Phan, Anurag Acharya, Rounak Meyur, Sarthak Chaturvedi, Shivam Sharma, Mike Parker, Dan Nally, Ali Jannesari, Karl Pazdernik, Mahantesh Halappanavar, Sai Munikoti, Sameera Horawalavithana
conference: "Arxiv"
year: 2024
bibkey: phan2024examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07321"}
tags: ['RAG', 'Model Architecture', 'Applications', 'GPT']
---
As LLMs become increasingly ubiquitous, researchers have tried various
techniques to augment the knowledge provided to these models. Long context and
retrieval-augmented generation (RAG) are two such methods that have recently
gained popularity. In this work, we examine the benefits of both of these
techniques by utilizing question answering (QA) task in a niche domain. While
the effectiveness of LLM-based QA systems has already been established at an
acceptable level in popular domains such as trivia and literature, it has not
often been established in niche domains that traditionally require specialized
expertise. We construct the NEPAQuAD1.0 benchmark to evaluate the performance
of five long-context LLMs -- Claude Sonnet, Gemini, GPT-4, Llama 3.1, and
Mistral -- when answering questions originating from Environmental Impact
Statements prepared by U.S. federal government agencies in accordance with the
National Environmental Environmental Act (NEPA). We specifically measure the
ability of LLMs to understand the nuances of legal, technical, and
compliance-related information present in NEPA documents in different
contextual scenarios. We test the LLMs' internal prior NEPA knowledge by
providing questions without any context, as well as assess how LLMs synthesize
the contextual information present in long NEPA documents to facilitate the
question/answering task. We compare the performance of the models in handling
different types of questions (e.g., problem-solving, divergent, etc.). Our
results suggest that RAG powered models significantly outperform those provided
with only the PDF context in terms of answer accuracy, regardless of the choice
of the LLM. Our further analysis reveals that many models perform better
answering closed type questions (Yes/No) than divergent and problem-solving
questions.
