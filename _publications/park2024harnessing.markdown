---
layout: publication
title: Loramap Harnessing The Power Of Lora Connections
authors: Park Hyeryun, Kwak Jeongwon, Jang Dongsuk, Park Sumin, Choi Jinwook
conference: "Arxiv"
year: 2024
bibkey: park2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16264"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture']
---
Large Language Models (LLMs) can benefit from mitigating hallucinations through fact45;checking and overcoming substantial computational overhead with parameter45;efficient techniques such as Low45;Rank Adaptation (LoRA). While some studies have explored the parallel integration of multiple LoRAs these approaches need attention to the connections between them. This paper investigates methods to establish connections among multiple LoRAs. We create three reasoning datasets tailored to fact45;checking and fine45;tune individual LoRAs allowing them to view and reason from diverse perspectives. Then we explore strategies for allocating these reasoning LoRAs and introduce LoraMap an approach to map connections between them. The results on the fact45;checking task demonstrate that the performance of LoraMap is superior to LoraHub an existing LoRA composition method. LoraMap also outperforms with significantly fewer parameters than LoraConcat which concatenates LoRAs and further fine45;tunes them.
