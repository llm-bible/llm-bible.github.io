---
layout: publication
title: 'Reinforcement Learning For Optimizing RAG For Domain Chatbots'
authors: Mandar Kulkarni, Praveen Tangarajan, Kyung Kim, Anusua Trivedi
conference: "Arxiv"
year: 2024
bibkey: kulkarni2024reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.06800'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'BERT', 'GPT', 'Reinforcement Learning']
---
With the advent of Large Language Models (LLM), conversational assistants
have become prevalent for domain use cases. LLMs acquire the ability to
contextual question answering through training, and Retrieval Augmented
Generation (RAG) further enables the bot to answer domain-specific questions.
This paper describes a RAG-based approach for building a chatbot that answers
user's queries using Frequently Asked Questions (FAQ) data. We train an
in-house retrieval embedding model using infoNCE loss, and experimental results
demonstrate that the in-house model works significantly better than the
well-known general-purpose public embedding model, both in terms of retrieval
accuracy and Out-of-Domain (OOD) query detection. As an LLM, we use an open
API-based paid ChatGPT model. We noticed that a previously retrieved-context
could be used to generate an answer for specific patterns/sequences of queries
(e.g., follow-up queries). Hence, there is a scope to optimize the number of
LLM tokens and cost. Assuming a fixed retrieval model and an LLM, we optimize
the number of LLM tokens using Reinforcement Learning (RL). Specifically, we
propose a policy-based model external to the RAG, which interacts with the RAG
pipeline through policy actions and updates the policy to optimize the cost.
The policy model can perform two actions: to fetch FAQ context or skip
retrieval. We use the open API-based GPT-4 as the reward model. We then train a
policy model using policy gradient on multiple training chat sessions. As a
policy model, we experimented with a public gpt-2 model and an in-house BERT
model. With the proposed RL-based optimization combined with similarity
threshold, we are able to achieve significant cost savings while getting a
slightly improved accuracy. Though we demonstrate results for the FAQ chatbot,
the proposed RL approach is generic and can be experimented with any existing
RAG pipeline.
