---
layout: publication
title: Poisoned LangChain Jailbreak LLMs by LangChain
authors: Wang Ziqiu, Liu Jun, Zhang Shengkai, Yang Yang
conference: "Arxiv"
year: 2024
bibkey: wang2024poisoned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18122"}
tags: ['Applications', 'Arxiv']
---
With the development of natural language processing (NLP) large language models (LLMs) are becoming increasingly popular. LLMs are integrating more into everyday life raising public concerns about their security vulnerabilities. Consequently the security of large language models is becoming critically important. Currently the techniques for attacking and defending against LLMs are continuously evolving. One significant method type of attack is the jailbreak attack which designed to evade model safety mechanisms and induce the generation of inappropriate content. Existing jailbreak attacks primarily rely on crafting inducement prompts for direct jailbreaks which are less effective against large models with robust filtering and high comprehension abilities. Given the increasing demand for real-time capabilities in large language models real-time updates and iterations of new knowledge have become essential. Retrieval-Augmented Generation (RAG) an advanced technique to compensate for the models lack of new knowledge is gradually becoming mainstream. As RAG enables the model to utilize external knowledge bases it provides a new avenue for jailbreak attacks. In this paper we conduct the first work to propose the concept of indirect jailbreak and achieve Retrieval-Augmented Generation via LangChain. Building on this we further design a novel method of indirect jailbreak attack termed Poisoned-LangChain (PLC) which leverages a poisoned external knowledge base to interact with large language models thereby causing the large models to generate malicious non-compliant dialogues.We tested this method on six different large language models across three major categories of jailbreak issues. The experiments demonstrate that PLC successfully implemented indirect jailbreak attacks under three different scenarios achieving success rates of 88.56 79.04 and 82.69 respectively.
