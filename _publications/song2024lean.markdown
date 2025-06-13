---
layout: publication
title: 'Lean Copilot: Large Language Models As Copilots For Theorem Proving In Lean'
authors: Peiyang Song, Kaiyu Yang, Anima Anandkumar
conference: "Arxiv"
year: 2024
bibkey: song2024lean
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.12534'}
tags: ['RAG', 'Tools']
---
Neural theorem proving combines large language models (LLMs) with proof assistants such as Lean, where the correctness of formal proofs can be rigorously verified, leaving no room for hallucination. With existing neural theorem provers pretrained on a fixed collection of data and offering valuable suggestions at times, it is challenging for them to continually prove novel theorems in a fully autonomous mode, where human insights may be critical. In this paper, we explore LLMs as copilots that assist humans in proving theorems. We introduce Lean Copilot, a general framework for running LLM inference natively in Lean. It enables programmers to build various LLM-based proof automation tools that integrate seamlessly into the workflow of Lean users. Lean users can use our pretrained models or bring their own ones that run either locally (with or without GPUs) or on the cloud. Using Lean Copilot, we build LLM-based tools that suggest proof steps, complete proof goals, and select relevant premises. Experimental results on the Mathematics in Lean textbook demonstrate the effectiveness of our method compared to existing rule-based proof automation in Lean (aesop). When assisting humans, Lean Copilot requires only 2.08 manually-entered proof steps on average (3.86 required by aesop); when automating the theorem proving process, Lean Copilot automates 74.2% proof steps on average, 85% better than aesop (40.1%). We open source all code and artifacts under a permissive MIT license to facilitate further research.
