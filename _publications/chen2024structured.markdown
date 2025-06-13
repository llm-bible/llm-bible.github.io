---
layout: publication
title: 'Structured Dialogue System For Mental Health: An LLM Chatbot Leveraging The PM+ Guidelines'
authors: Yixiang Chen, Xinyu Zhang, Jinran Wang, Xurong Xie, Nan Yan, Hui Chen, Lan Wang
conference: "Arxiv"
year: 2024
bibkey: chen2024structured
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10681'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The Structured Dialogue System, referred to as SuDoSys, is an innovative
Large Language Model (LLM)-based chatbot designed to provide psychological
counseling. SuDoSys leverages the World Health Organization (WHO)'s Problem
Management Plus (PM+) guidelines to deliver stage-aware multi-turn dialogues.
Existing methods for employing an LLM in multi-turn psychological counseling
typically involve direct fine-tuning using generated dialogues, often
neglecting the dynamic stage shifts of counseling sessions. Unlike previous
approaches, SuDoSys considers the different stages of counseling and stores
essential information throughout the counseling process, ensuring coherent and
directed conversations. The system employs an LLM, a stage-aware instruction
generator, a response unpacker, a topic database, and a stage controller to
maintain dialogue flow. In addition, we propose a novel technique that
simulates counseling clients to interact with the evaluated system and evaluate
its performance automatically. When assessed using both objective and
subjective evaluations, SuDoSys demonstrates its effectiveness in generating
logically coherent responses. The system's code and program scripts for
evaluation are open-sourced.
