---
layout: publication
title: 'Faclens: Transferable Probe For Foreseeing Non-factuality In Large Language Models'
authors: Yanling Wang, Haoyang Li, Hao Zou, Jing Zhang, Xinlei He, Qi Li, Ke Xu
conference: "Arxiv"
year: 2024
bibkey: wang2024transferable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05328"}
tags: ['ACL', 'Efficiency and Optimization']
---
Despite advancements in large language models (LLMs), non-factual responses
remain prevalent. Unlike extensive studies on post-hoc detection of such
responses, this work studies non-factuality prediction (NFP), aiming to predict
whether an LLM will generate a non-factual response to a question before the
generation process. Previous efforts on NFP have demonstrated LLMs' awareness
of their internal knowledge, but they still face challenges in efficiency and
transferability. In this work, we propose a lightweight NFP model named
Factuality Lens (FacLens), which effectively probes hidden representations of
questions for the NFP task. Besides, we discover that hidden question
representations sourced from different LLMs exhibit similar NFP patterns, which
enables the transferability of FacLens across LLMs to reduce development costs.
Extensive experiments highlight FacLens's superiority in both effectiveness and
efficiency.
