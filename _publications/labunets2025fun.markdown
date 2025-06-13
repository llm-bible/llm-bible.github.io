---
layout: publication
title: 'Fun-tuning: Characterizing The Vulnerability Of Proprietary Llms To Optimization-based Prompt Injection Attacks Via The Fine-tuning Interface'
authors: Andrey Labunets, Nishit V. Pandya, Ashish Hooda, Xiaohan Fu, Earlence Fernandes
conference: "Proceedings of the 2025 IEEE Symposium on Security and Privacy IEEE Computer Society 2025 pp. 374-392"
year: 2025
bibkey: labunets2025fun
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09798"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
We surface a new threat to closed-weight Large Language Models (LLMs) that enables an attacker to compute optimization-based prompt injections. Specifically, we characterize how an attacker can leverage the loss-like information returned from the remote fine-tuning interface to guide the search for adversarial prompts. The fine-tuning interface is hosted by an LLM vendor and allows developers to fine-tune LLMs for their tasks, thus providing utility, but also exposes enough information for an attacker to compute adversarial prompts. Through an experimental analysis, we characterize the loss-like values returned by the Gemini fine-tuning API and demonstrate that they provide a useful signal for discrete optimization of adversarial prompts using a greedy search algorithm. Using the PurpleLlama prompt injection benchmark, we demonstrate attack success rates between 65% and 82% on Google's Gemini family of LLMs. These attacks exploit the classic utility-security tradeoff - the fine-tuning interface provides a useful feature for developers but also exposes the LLMs to powerful attacks.
