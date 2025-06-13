---
layout: publication
title: 'Reasoning Limitations Of Multimodal Large Language Models. A Case Study Of Bongard Problems'
authors: Mikołaj Małkiński, Szymon Pawlonka, Jacek Mańdziuk
conference: "Arxiv"
year: 2024
bibkey: małkiński2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01173"}
tags: ['GPT', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning']
---
Abstract visual reasoning (AVR) encompasses a suite of tasks whose solving
requires the ability to discover common concepts underlying the set of pictures
through an analogy-making process, similarly to human IQ tests. Bongard
Problems (BPs), proposed in 1968, constitute a fundamental challenge in this
domain mainly due to their requirement to combine visual reasoning and verbal
description. This work poses a question whether multimodal large language
models (MLLMs) inherently designed to combine vision and language are capable
of tackling BPs. To this end, we propose a set of diverse MLLM-suited
strategies to tackle BPs and examine four popular proprietary MLLMs: GPT-4o,
GPT-4 Turbo, Gemini 1.5 Pro, and Claude 3.5 Sonnet, and four open models:
InternVL2-8B, LLaVa-1.6 Mistral-7B, Phi-3.5-Vision, and Pixtral 12B. The above
MLLMs are compared on three BP datasets: a set of original BP instances relying
on synthetic, geometry-based images and two recent datasets based on real-world
images, i.e., Bongard-HOI and Bongard-OpenWorld. The experiments reveal
significant limitations of MLLMs in solving BPs. In particular, the models
struggle to solve the classical set of synthetic BPs, despite their visual
simplicity. Though their performance ameliorates on real-world concepts
expressed in Bongard-HOI and Bongard-OpenWorld, the models still have
difficulty in utilizing new information to improve their predictions, as well
as utilizing a dialog context window effectively. To capture the reasons of
performance discrepancy between synthetic and real-world AVR domains, we
propose Bongard-RWR, a new BP dataset consisting of real-world images that
translates concepts from hand-crafted synthetic BPs to real-world concepts. The
MLLMs' results on Bongard-RWR suggest that their poor performance on classical
BPs is not due to domain specificity but rather reflects their general AVR
limitations.
