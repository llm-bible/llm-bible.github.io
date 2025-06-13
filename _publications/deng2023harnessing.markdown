---
layout: publication
title: 'Harnessing LLM To Attack Llm-guarded Text-to-image Models'
authors: Yimo Deng, Huangxun Chen
conference: "Arxiv"
year: 2023
bibkey: deng2023harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.07130'}
  - {name: "Code", url: 'https://github.com/researchcode003/DACA)'}
tags: ['Agentic', 'Has Code', 'Security', 'Prompting', 'Responsible AI']
---
To prevent Text-to-Image (T2I) models from generating unethical images,
people deploy safety filters to block inappropriate drawing prompts. Previous
works have employed token replacement to search adversarial prompts that
attempt to bypass these filters, but they have become ineffective as
nonsensical tokens fail semantic logic checks. In this paper, we approach
adversarial prompts from a different perspective. We demonstrate that
rephrasing a drawing intent into multiple benign descriptions of individual
visual components can obtain an effective adversarial prompt. We propose a
LLM-piloted multi-agent method named DACA to automatically complete intended
rephrasing. Our method successfully bypasses the safety filters of DALL-E 3 and
Midjourney to generate the intended images, achieving success rates of up to
76.7% and 64% in the one-time attack, and 98% and 84% in the re-use attack,
respectively. We open-source our code and dataset on [this
link](https://github.com/researchcode003/DACA).
