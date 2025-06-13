---
layout: publication
title: 'On The Way To LLM Personalization: Learning To Remember User Conversations'
authors: Lucie Charlotte Magister, Katherine Metcalf, Yizhe Zhang, Maartje Ter Hoeve
conference: "Arxiv"
year: 2024
bibkey: magister2024way
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13405"}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
Large Language Models (LLMs) have quickly become an invaluable assistant for
a variety of tasks. However, their effectiveness is constrained by their
ability to tailor responses to human preferences and behaviors via
personalization. Prior work in LLM personalization has largely focused on style
transfer or incorporating small factoids about the user, as knowledge injection
remains an open challenge. In this paper, we explore injecting knowledge of
prior conversations into LLMs to enable future work on less redundant,
personalized conversations. We identify two real-world constraints: (1)
conversations are sequential in time and must be treated as such during
training, and (2) per-user personalization is only viable in
parameter-efficient settings. To this aim, we propose PLUM, a pipeline
performing data augmentation for up-sampling conversations as question-answer
pairs, that are then used to finetune a low-rank adaptation adapter with a
weighted cross entropy loss. Even in this first exploration of the problem, we
perform competitively with baselines such as RAG, attaining an accuracy of
81.5% across 100 conversations.
