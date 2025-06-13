---
layout: publication
title: 'When To Speak, When To Abstain: Contrastive Decoding With Abstention'
authors: Hyuhng Joon Kim, Youna Kim, Sang-goo Lee, Taeuk Kim
conference: "Arxiv"
year: 2024
bibkey: kim2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12527"}
tags: ['Security', 'Training Techniques', 'RAG']
---
Large Language Models (LLMs) demonstrate exceptional performance across diverse tasks by leveraging pre-trained (i.e., parametric) and external (i.e., contextual) knowledge. While substantial efforts have been made to enhance the utilization of both forms of knowledge, situations in which models lack relevant information remain underexplored. To investigate this challenge, we first present a controlled testbed featuring four distinct knowledge access scenarios, including the aforementioned edge case, revealing that conventional LLM usage exhibits insufficient robustness in handling all instances. Addressing this limitation, we propose Contrastive Decoding with Abstention (CDA), a novel training-free decoding method that allows LLMs to generate responses when relevant knowledge is available and to abstain otherwise. CDA estimates the relevance of both knowledge sources for a given input, adaptively deciding which type of information to prioritize and which to exclude. Through extensive experiments, we demonstrate that CDA can effectively perform accurate generation and abstention simultaneously, enhancing reliability and preserving user trust.
