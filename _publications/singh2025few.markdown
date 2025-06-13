---
layout: publication
title: 'FSPO: Few-shot Preference Optimization Of Synthetic Preference Data In Llms Elicits Effective Personalization To Real Users'
authors: Anikait Singh, Sheryl Hsu, Kyle Hsu, Eric Mitchell, Stefano Ermon, Tatsunori Hashimoto, Archit Sharma, Chelsea Finn
conference: "Arxiv"
year: 2025
bibkey: singh2025few
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19312'}
tags: ['Few-Shot', 'RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Effective personalization of LLMs is critical for a broad range of
user-interfacing applications such as virtual assistants and content curation.
Inspired by the strong in-context learning capabilities of LLMs, we propose
Few-Shot Preference Optimization (FSPO), which reframes reward modeling as a
meta-learning problem. Under this framework, an LLM learns to quickly adapt to
a user via a few labeled preferences from that user, constructing a
personalized reward function for them. Additionally, since real-world
preference data is scarce and challenging to collect at scale, we propose
careful design choices to construct synthetic preference datasets for
personalization, generating over 1M synthetic personalized preferences using
publicly available LLMs. In particular, to successfully transfer from synthetic
data to real users, we find it crucial for the data to exhibit both high
diversity and coherent, self-consistent structure. We evaluate FSPO on
personalized open-ended generation for up to 1,500 synthetic users across
across three domains: movie reviews, pedagogical adaptation based on
educational background, and general question answering, along with a controlled
human study. Overall, FSPO achieves an 87% Alpaca Eval winrate on average in
generating responses that are personalized to synthetic users and a 72% winrate
with real human users in open-ended question answering.
