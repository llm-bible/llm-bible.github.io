---
layout: publication
title: Towards LogiGLUE A Brief Survey and A Benchmark for Analyzing Logical Reasoning Capabilities of Language Models
authors: Luo Man, Kumbhar Shrinidhi, Shen Ming, Parmar Mihir, Varshney Neeraj, Banerjee Pratyay, Aditya Somak, Baral Chitta
conference: "Arxiv"
year: 2023
bibkey: luo2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00836"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Survey Paper', 'Training Techniques']
---
Logical reasoning is fundamental for humans yet presents a substantial challenge in the domain of Artificial Intelligence. Initially researchers used Knowledge Representation and Reasoning (KR) systems that did not scale and required non-trivial manual effort. Recently the emergence of large language models (LLMs) has demonstrated the ability to overcome various limitations of formal Knowledge Representation (KR) systems. Consequently theres a growing interest in using LLMs for logical reasoning via natural language. This work strives to understand the proficiency of LLMs in logical reasoning by offering a brief review of the latest progress in this area; with a focus on the logical reasoning datasets tasks and the methods adopted to utilize LLMs for reasoning. To offer a thorough analysis we have compiled a benchmark titled LogiGLUE. This includes 24 varied datasets encompassing deductive abductive and inductive reasoning. Utilizing LogiGLUE as a foundation we have trained an instruction fine-tuned language model resulting in LogiT5. We study single-task training multi-task training and chain-of-thought knowledge distillation fine-tuning technique to assess the performance of model across the different logical reasoning categories. We also assess various LLMs using LogiGLUE and the findings indicate that LLMs excel most in abductive reasoning followed by deductive reasoning while they are least effective at inductive reasoning. We aim to shed light on the capabilities and potential pathways for enhancing logical reasoning proficiency in LLMs paving the way for more advanced and nuanced developments in this critical field.
