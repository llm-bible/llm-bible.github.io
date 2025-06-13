---
layout: publication
title: 'Backdoored Retrievers For Prompt Injection Attacks On Retrieval Augmented Generation Of Large Language Models'
authors: Cody Clop, Yannick Teglia
conference: "Arxiv"
year: 2024
bibkey: clop2024backdoored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14479"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
generating coherent text but remain limited by the static nature of their
training data. Retrieval Augmented Generation (RAG) addresses this issue by
combining LLMs with up-to-date information retrieval, but also expand the
attack surface of the system. This paper investigates prompt injection attacks
on RAG, focusing on malicious objectives beyond misinformation, such as
inserting harmful links, promoting unauthorized services, and initiating
denial-of-service behaviors. We build upon existing corpus poisoning techniques
and propose a novel backdoor attack aimed at the fine-tuning process of the
dense retriever component. Our experiments reveal that corpus poisoning can
achieve significant attack success rates through the injection of a small
number of compromised documents into the retriever corpus. In contrast,
backdoor attacks demonstrate even higher success rates but necessitate a more
complex setup, as the victim must fine-tune the retriever using the attacker
poisoned dataset.
