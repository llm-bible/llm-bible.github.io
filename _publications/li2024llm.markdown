---
layout: publication
title: LLM Defenses Are Not Robust To Multi-turn Human Jailbreaks Yet
authors: Li Nathaniel, Han Ziwen, Steneker Ian, Primack Willow, Goodside Riley, Zhang Hugh, Wang Zifan, Menghini Cristina, Yue Summer
conference: "Arxiv"
year: 2024
bibkey: li2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15221"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security']
---
Recent large language model (LLM) defenses have greatly improved models ability to refuse harmful queries even when adversarially attacked. However LLM defenses are primarily evaluated against automated adversarial attacks in a single turn of conversation an insufficient threat model for real-world malicious use. We demonstrate that multi-turn human jailbreaks uncover significant vulnerabilities exceeding 7037; attack success rate (ASR) on HarmBench against defenses that report single-digit ASRs with automated single-turn attacks. Human jailbreaks also reveal vulnerabilities in machine unlearning defenses successfully recovering dual-use biosecurity knowledge from unlearned models. We compile these results into Multi-Turn Human Jailbreaks (MHJ) a dataset of 2912 prompts across 537 multi-turn jailbreaks. We publicly release MHJ alongside a compendium of jailbreak tactics developed across dozens of commercial red teaming engagements supporting research towards stronger LLM defenses.
