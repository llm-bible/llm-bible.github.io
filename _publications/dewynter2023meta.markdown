---
layout: publication
title: 'On Meta-prompting'
authors: Adrian De Wynter, Xun Wang, Qilong Gu, Si-qing Chen
conference: "Arxiv"
year: 2023
bibkey: dewynter2023meta
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.06562'}
tags: ['Training Techniques', 'Tools', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Modern large language models (LLMs) are capable of interpreting input strings as instructions, or prompts, and carry out tasks based on them. Unlike traditional learners, LLMs cannot use back-propagation to obtain feedback, and condition their output in situ in a phenomenon known as in-context learning (ICL). Many approaches to prompting and pre-training these models involve the automated generation of these prompts, also known as meta-prompting, or prompting to obtain prompts. However, they do not formally describe the properties and behavior of the LLMs themselves. We propose a theoretical framework based on category theory to generalize and describe ICL and LLM behavior when interacting with users. Our framework allows us to obtain formal results around task agnosticity and equivalence of various meta-prompting approaches. Using our framework and experimental results we argue that meta-prompting is more effective than basic prompting at generating desirable outputs.
