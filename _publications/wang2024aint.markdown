---
layout: publication
title: Aint Misbehavin -- Using Llms To Generate Expressive Robot Behavior In Conversations With The Tabletop Robot Haru
authors: Wang Zining, Reisert Paul, Nichols Eric, Gomez Randy
conference: "Companion of HRI"
year: 2024
bibkey: wang2024aint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11571"}
tags: ['Pretraining Methods', 'RAG', 'Tools']
---
Social robots aim to establish long-term bonds with humans through engaging conversation. However traditional conversational approaches reliant on scripted interactions often fall short in maintaining engaging conversations. This paper addresses this limitation by integrating large language models (LLMs) into social robots to achieve more dynamic and expressive conversations. We introduce a fully-automated conversation system that leverages LLMs to generate robot responses with expressive behaviors congruent with the robots personality. We incorporate robot behavior with two modalities 1) a text-to-speech (TTS) engine capable of various delivery styles and 2) a library of physical actions for the robot. We develop a custom state-of-the-art emotion recognition model to dynamically select the robots tone of voice and utilize emojis from LLM output as cues for generating robot actions. A demo of our system is available here. To illuminate design and implementation issues we conduct a pilot study where volunteers chat with a social robot using our proposed system and we analyze their feedback conducting a rigorous error analysis of chat transcripts. Feedback was overwhelmingly positive with participants commenting on the robots empathy helpfulness naturalness and entertainment. Most negative feedback was due to automatic speech recognition (ASR) errors which had limited impact on conversations. However we observed a small class of errors such as the LLM repeating itself or hallucinating fictitious information and human responses that have the potential to derail conversations raising important issues for LLM application.
