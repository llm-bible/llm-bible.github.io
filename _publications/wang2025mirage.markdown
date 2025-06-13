---
layout: publication
title: 'Mirage In The Eyes: Hallucination Attack On Multi-modal Large Language Models With Only Attention Sink'
authors: Yining Wang, Mi Zhang, Junjie Sun, Chenyue Wang, Min Yang, Hui Xue, Jialing Tao, Ranjie Duan, Jiexi Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025mirage
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.15269'}
  - {name: "Code", url: 'https://huggingface.co/RachelHGF/Mirage-in-the-Eyes'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Security', 'Model Architecture', 'Tools', 'Applications', 'Fine-Tuning', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
Fusing visual understanding into language generation, Multi-modal Large
Language Models (MLLMs) are revolutionizing visual-language applications. Yet,
these models are often plagued by the hallucination problem, which involves
generating inaccurate objects, attributes, and relationships that do not match
the visual content. In this work, we delve into the internal attention
mechanisms of MLLMs to reveal the underlying causes of hallucination, exposing
the inherent vulnerabilities in the instruction-tuning process.
  We propose a novel hallucination attack against MLLMs that exploits attention
sink behaviors to trigger hallucinated content with minimal image-text
relevance, posing a significant threat to critical downstream applications.
Distinguished from previous adversarial methods that rely on fixed patterns,
our approach generates dynamic, effective, and highly transferable visual
adversarial inputs, without sacrificing the quality of model responses.
Comprehensive experiments on 6 prominent MLLMs demonstrate the efficacy of our
attack in compromising black-box MLLMs even with extensive mitigating
mechanisms, as well as the promising results against cutting-edge commercial
APIs, such as GPT-4o and Gemini 1.5. Our code is available at
https://huggingface.co/RachelHGF/Mirage-in-the-Eyes.
