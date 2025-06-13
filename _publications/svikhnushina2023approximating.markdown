---
layout: publication
title: 'Approximating Online Human Evaluation Of Social Chatbots With Prompting'
authors: Ekaterina Svikhnushina, Pearl Pu
conference: "Arxiv"
year: 2023
bibkey: svikhnushina2023approximating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.05253"}
tags: ['Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
As conversational models become increasingly available to the general public,
users are engaging with this technology in social interactions. Such
unprecedented interaction experiences may pose considerable social and
psychological risks to the users unless the technology is properly controlled.
This highlights the need for scalable and robust evaluation metrics for
conversational chatbots. Existing evaluation metrics aim to automate offline
user evaluation and approximate human judgment of pre-curated dialogs. However,
they are limited in their ability to capture subjective perceptions of users
who actually interact with the bots and might not generalize to real-world
settings. To address this limitation, we propose an approach to approximate
online human evaluation leveraging large language models (LLMs) from the GPT
family. We introduce a new Dialog system Evaluation framework based on
Prompting (DEP), which enables a fully automatic evaluation pipeline that
replicates live user studies and achieves an impressive correlation with human
judgment (up to Pearson r=0.95 on a system level). The DEP approach involves
collecting synthetic chat logs of evaluated bots with an LLM in the other-play
setting, where the LLM is carefully conditioned to follow a specific scenario.
We further explore different prompting approaches to produce evaluation scores
with the same LLM. The best performing prompts, which contain few-shot
demonstrations and instructions, show outstanding performance on the tested
dataset and demonstrate the ability to generalize to other dialog corpora.
