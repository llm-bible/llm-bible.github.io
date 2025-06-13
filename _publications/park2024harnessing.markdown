---
layout: publication
title: 'Loramap: Harnessing The Power Of Lora Connections'
authors: Hyeryun Park, Jeongwon Kwak, Dongsuk Jang, Sumin Park, Jinwook Choi
conference: "Arxiv"
year: 2024
bibkey: park2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16264"}
tags: ['Fine-Tuning']
---
Fact-checking techniques can mitigate hallucinations in Large Language Models
(LLMs), a prominent issue in specialized domains. As parameter-efficient
techniques such as Low-Rank Adaptation (LoRA) can overcome substantial
computational overhead, some studies have explored the integration of multiple
LoRAs. While previous studies focus on parallel integration, this paper
investigates methods to establish connections among multiple LoRAs. We create
three reasoning datasets tailored to fact-checking and fine-tune individual
LoRAs, allowing them to view and reason from diverse perspectives. Then, we
explore strategies for allocating these reasoning LoRAs and introduce LoraMap,
an approach to map connections between them. The results of the fact-checking
task demonstrate that the performance of LoraMap is superior to LoraHub, an
existing method for integrating LoRAs. LoraMap also outperforms with
significantly fewer trainable parameters than LoraConcat, which concatenates
LoRAs and further fine-tunes them.
