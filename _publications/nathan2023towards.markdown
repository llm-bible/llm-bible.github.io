---
layout: publication
title: 'Towards Probing Contact Center Large Language Models'
authors: Varun Nathan, Ayush Kumar, Digvijay Ingle, Jithendra Vepa
conference: "Arxiv"
year: 2023
bibkey: nathan2023towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.15922'}
tags: ['INTERSPEECH', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) with domain-specific instructions
has emerged as an effective method to enhance their domain-specific
understanding. Yet, there is limited work that examines the core
characteristics acquired during this process. In this study, we benchmark the
fundamental characteristics learned by contact-center (CC) specific instruction
fine-tuned LLMs with out-of-the-box (OOB) LLMs via probing tasks encompassing
conversational, channel, and automatic speech recognition (ASR) properties. We
explore different LLM architectures (Flan-T5 and Llama), sizes (3B, 7B, 11B,
13B), and fine-tuning paradigms (full fine-tuning vs PEFT). Our findings reveal
remarkable effectiveness of CC-LLMs on the in-domain downstream tasks, with
improvement in response acceptability by over 48% compared to OOB-LLMs.
Additionally, we compare the performance of OOB-LLMs and CC-LLMs on the widely
used SentEval dataset, and assess their capabilities in terms of surface,
syntactic, and semantic information through probing tasks. Intriguingly, we
note a relatively consistent performance of probing classifiers on the set of
probing tasks. Our observations indicate that CC-LLMs, while outperforming
their out-of-the-box counterparts, exhibit a tendency to rely less on encoding
surface, syntactic, and semantic properties, highlighting the intricate
interplay between domain-specific adaptation and probing task performance
opening up opportunities to explore behavior of fine-tuned language models in
specialized contexts.
