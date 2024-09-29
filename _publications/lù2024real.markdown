---
layout: publication
title: Weblinx Real45;world Website Navigation With Multi45;turn Dialogue
authors: Lù Xing Han, Kasner Zdeněk, Reddy Siva
conference: "Arxiv"
year: 2024
bibkey: lù2024real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05930"}
  - {name: "Code", url: "https://mcgill&#45;nlp.github.io/weblinx"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
We propose the problem of conversational web navigation where a digital agent controls a web browser and follows user instructions to solve real45;world tasks in a multi45;turn dialogue fashion. To support this problem we introduce WEBLINX 45; a large45;scale benchmark of 100K interactions across 2300 expert demonstrations of conversational web navigation. Our benchmark covers a broad range of patterns on over 150 real45;world websites and can be used to train and evaluate agents in diverse scenarios. Due to the magnitude of information present Large Language Models (LLMs) cannot process entire web pages in real45;time. To solve this bottleneck we design a retrieval45;inspired model that efficiently prunes HTML pages by ranking relevant elements. We use the selected elements along with screenshots and action history to assess a variety of models for their ability to replicate human behavior when navigating the web. Our experiments span from small text45;only to proprietary multimodal LLMs. We find that smaller finetuned decoders surpass the best zero45;shot LLMs (including GPT45;4V) but also larger finetuned multimodal models which were explicitly pretrained on screenshots. However all finetuned models struggle to generalize to unseen websites. Our findings highlight the need for large multimodal models that can generalize to novel settings. Our code data and models are available for research https://mcgill&#45;nlp.github.io/weblinx
