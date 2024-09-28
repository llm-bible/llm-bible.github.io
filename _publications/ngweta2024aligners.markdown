---
layout: publication
title: Aligners Decoupling LLMs and Alignment
authors: Ngweta Lilian, Agarwal Mayank, Maity Subha, Gittens Alex, Sun Yuekai, Yurochkin Mikhail
conference: "Arxiv"
year: 2024
bibkey: ngweta2024aligners
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04224"}
tags: ['ARXIV', 'Applications', 'LLM', 'Prompt', 'Responsible AI']
---
Large Language Models (LLMs) need to be aligned with human expectations to ensure their safety and utility in most applications. Alignment is challenging costly and needs to be repeated for every LLM and alignment criterion. We propose to decouple LLMs and alignment by training aligner models that can be used to align any LLM for a given criteria on an as-needed basis thus also reducing the potential negative impacts of alignment on performance. Our recipe for training the aligner models solely relies on synthetic data generated with a (prompted) LLM and can be easily adjusted for a variety of alignment criteria. We use the same synthetic data to train inspectors binary miss-alignment classification models to guide a squad of multiple aligners. Our empirical results demonstrate consistent improvements when applying aligner squad to various LLMs including chat-aligned models across several instruction-following and red-teaming datasets.
