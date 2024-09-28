---
layout: publication
title: Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM
authors: Cao Bochuan, Cao Yuanpu, Lin Lu, Chen Jinghui
conference: "Arxiv"
year: 2023
bibkey: cao2023defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14348"}
tags: ['ARXIV', 'Pretraining Methods']
---
Recently Large Language Models (LLMs) have made significant advancements and are now widely used across various domains. Unfortunately there has been a rising concern that LLMs can be misused to generate harmful or malicious content. Though a line of research has focused on aligning LLMs with human values and preventing them from producing inappropriate content such alignments are usually vulnerable and can be bypassed by alignment-breaking attacks via adversarially optimized or handcrafted jailbreaking prompts. In this work we introduce a Robustly Aligned LLM (RA-LLM) to defend against potential alignment-breaking attacks. RA-LLM can be directly constructed upon an existing aligned LLM with a robust alignment checking function without requiring any expensive retraining or fine-tuning process of the original LLM. Furthermore we also provide a theoretical analysis for RA-LLM to verify its effectiveness in defending against alignment-breaking attacks. Through real-world experiments on open-source large language models we demonstrate that RA-LLM can successfully defend against both state-of-the-art adversarial prompts and popular handcrafted jailbreaking prompts by reducing their attack success rates from nearly 100 to around 10 or less.
