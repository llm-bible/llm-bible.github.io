---
layout: publication
title: 'Cogagent: A Visual Language Model For GUI Agents'
authors: Wenyi Hong et al.
conference: Arxiv
year: 2023
citations: 37
bibkey: hong2023visual
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.08914'}, {name: Code,
    url: 'https://github.com/THUDM/CogVLM,'}, {name: Code, url: 'https://github.com/THUDM/CogAgent'}]
tags: [Agentic, Reinforcement Learning, GPT]
---
People are spending an enormous amount of time on digital devices through
graphical user interfaces (GUIs), e.g., computer or smartphone screens. Large
language models (LLMs) such as ChatGPT can assist people in tasks like writing
emails, but struggle to understand and interact with GUIs, thus limiting their
potential to increase automation levels. In this paper, we introduce CogAgent,
an 18-billion-parameter visual language model (VLM) specializing in GUI
understanding and navigation. By utilizing both low-resolution and
high-resolution image encoders, CogAgent supports input at a resolution of
1120*1120, enabling it to recognize tiny page elements and text. As a
generalist visual language model, CogAgent achieves the state of the art on
five text-rich and four general VQA benchmarks, including VQAv2, OK-VQA,
Text-VQA, ST-VQA, ChartQA, infoVQA, DocVQA, MM-Vet, and POPE. CogAgent, using
only screenshots as input, outperforms LLM-based methods that consume extracted
HTML text on both PC and Android GUI navigation tasks -- Mind2Web and AITW,
advancing the state of the art. The model and codes are available at
https://github.com/THUDM/CogVLM, with a new version of CogAgent-9B-20241220
available at https://github.com/THUDM/CogAgent.