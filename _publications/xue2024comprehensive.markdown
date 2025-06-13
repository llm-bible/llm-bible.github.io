---
layout: publication
title: 'Mlingconf: A Comprehensive Study Of Multilingual Confidence Estimation On Large Language Models'
authors: Boyang Xue, Hongru Wang, Rui Wang, Sheng Wang, Zezhong Wang, Yiming Du, Bin Liang, Kam-fai Wong
conference: "Arxiv"
year: 2024
bibkey: xue2024comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.12478'}
tags: ['Prompting']
---
The tendency of Large Language Models (LLMs) to generate hallucinations
raises concerns regarding their reliability. Therefore, confidence estimations
indicating the extent of trustworthiness of the generations become essential.
However, current LLM confidence estimations in languages other than English
remain underexplored. This paper addresses this gap by introducing a
comprehensive investigation of Multilingual Confidence estimation (MlingConf)
on LLMs, focusing on both language-agnostic (LA) and language-specific (LS)
tasks to explore the performance and language dominance effects of multilingual
confidence estimations on different tasks. The benchmark comprises four
meticulously checked and human-evaluate high-quality multilingual datasets for
LA tasks and one for the LS task tailored to specific social, cultural, and
geographical contexts of a language. Our experiments reveal that on LA tasks
English exhibits notable linguistic dominance in confidence estimations than
other languages, while on LS tasks, using question-related language to prompt
LLMs demonstrates better linguistic dominance in multilingual confidence
estimations. The phenomena inspire a simple yet effective native-tone prompting
strategy by employing language-specific prompts for LS tasks, effectively
improving LLMs' reliability and accuracy on LS tasks.
