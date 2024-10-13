---
layout: publication
title: 'Instruction-following Speech Recognition'
authors: Lai Cheng-i Jeff, Lu Zhiyun, Cao Liangliang, Pang Ruoming
conference: "Arxiv"
year: 2023
bibkey: lai2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.09843"}
tags: ['Applications', 'Prompting', 'Responsible AI', 'Training Techniques']
---
Conventional end-to-end Automatic Speech Recognition (ASR) models primarily
focus on exact transcription tasks, lacking flexibility for nuanced user
interactions. With the advent of Large Language Models (LLMs) in speech
processing, more organic, text-prompt-based interactions have become possible.
However, the mechanisms behind these models' speech understanding and
"reasoning" capabilities remain underexplored. To study this question from the
data perspective, we introduce instruction-following speech recognition,
training a Listen-Attend-Spell model to understand and execute a diverse set of
free-form text instructions. This enables a multitude of speech recognition
tasks -- ranging from transcript manipulation to summarization -- without
relying on predefined command sets. Remarkably, our model, trained from scratch
on Librispeech, interprets and executes simple instructions without requiring
LLMs or pre-trained speech modules. It also offers selective transcription
options based on instructions like "transcribe first half and then turn off
listening," providing an additional layer of privacy and safety compared to
existing LLMs. Our findings highlight the significant potential of
instruction-following training to advance speech foundation models.
