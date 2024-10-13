---
layout: publication
title: 'Roleplay-doh: Enabling Domain-experts To Create Llm-simulated Patients Via Eliciting And Adhering To Principles'
authors: Louie Ryan, Nandi Ananjan, Fang William, Chang Cheng, Brunskill Emma, Yang Diyi
conference: "Arxiv"
year: 2024
bibkey: louie2024roleplay
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00870"}
  - {name: "Code", url: "https://roleplay-doh.github.io/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Uncategorized']
---
Recent works leverage LLMs to roleplay realistic social scenarios, aiding
novices in practicing their social skills. However, simulating sensitive
interactions, such as in mental health, is challenging. Privacy concerns
restrict data access, and collecting expert feedback, although vital, is
laborious. To address this, we develop Roleplay-doh, a novel human-LLM
collaboration pipeline that elicits qualitative feedback from a domain-expert,
which is transformed into a set of principles, or natural language rules, that
govern an LLM-prompted roleplay. We apply this pipeline to enable senior mental
health supporters to create customized AI patients for simulated practice
partners for novice counselors. After uncovering issues in GPT-4 simulations
not adhering to expert-defined principles, we also introduce a novel
principle-adherence prompting pipeline which shows 30% improvements in response
quality and principle following for the downstream task. Via a user study with
25 counseling experts, we demonstrate that the pipeline makes it easy and
effective to create AI patients that more faithfully resemble real patients, as
judged by creators and third-party counselors. See our project website at
https://roleplay-doh.github.io/ for code and data.
