---
layout: publication
title: 'Understanding Long Videos With Multimodal Language Models'
authors: Kanchana Ranasinghe, Xiang Li, Kumara Kahatapitiya, Michael S. Ryoo
conference: "Arxiv"
year: 2024
bibkey: ranasinghe2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16998"}
  - {name: "Code", url: "https://github.com/kahnchana/mvu"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Has Code', 'Multimodal Models']
---
Large Language Models (LLMs) have allowed recent LLM-based approaches to
achieve excellent performance on long-video understanding benchmarks. We
investigate how extensive world knowledge and strong reasoning skills of
underlying LLMs influence this strong performance. Surprisingly, we discover
that LLM-based approaches can yield surprisingly good accuracy on long-video
tasks with limited video information, sometimes even with no video specific
information. Building on this, we explore injecting video-specific information
into an LLM-based framework. We utilize off-the-shelf vision tools to extract
three object-centric information modalities from videos, and then leverage
natural language as a medium for fusing this information. Our resulting
Multimodal Video Understanding (MVU) framework demonstrates state-of-the-art
performance across multiple video understanding benchmarks. Strong performance
also on robotics domain tasks establish its strong generality. Code:
https://github.com/kahnchana/mvu
