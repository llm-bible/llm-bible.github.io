---
layout: publication
title: Integrating Large Language Models With Graph-based Reasoning For Conversational Question Answering
authors: Jain Parag, Lapata Mirella
conference: "Arxiv"
year: 2024
bibkey: jain2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09506"}
tags: ['Applications', 'Language Modeling', 'Security']
---
We focus on a conversational question answering task which combines the challenges of understanding questions in context and reasoning over evidence gathered from heterogeneous sources like text knowledge graphs tables and infoboxes. Our method utilizes a graph structured representation to aggregate information about a question and its context (i.e. the conversation so far and evidence retrieved to find an answer) while also harnessing the reasoning and text generation capabilities of large language models (LLMs). Graph embeddings are directly injected into the LLM bypassing the token embedding layers and learned end-to-end by minimizing cross-entropy. Our model maintains a memory module to track and update past evidence thus influencing the graphs structure as the conversation evolves. Experimental results on the ConvMix benchmark(Christmann et al. 2022a) show that graph embeddings enhance the LLMs ability to reason while the memory module provides robustness against noise and retrieval errors.
