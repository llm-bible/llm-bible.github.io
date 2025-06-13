---
layout: publication
title: 'A Test Suite Of Prompt Injection Attacks For Llm-based Machine Translation'
authors: Antonio Valerio Miceli-barone, Zhifan Sun
conference: "Arxiv"
year: 2024
bibkey: micelibarone2024test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05047"}
tags: ['Security', 'Prompting', 'Applications', 'WMT']
---
LLM-based NLP systems typically work by embedding their input data into
prompt templates which contain instructions and/or in-context examples,
creating queries which are submitted to a LLM, and then parsing the LLM
response in order to generate the system outputs. Prompt Injection Attacks
(PIAs) are a type of subversion of these systems where a malicious user crafts
special inputs which interfere with the prompt templates, causing the LLM to
respond in ways unintended by the system designer.
  Recently, Sun and Miceli-Barone proposed a class of PIAs against LLM-based
machine translation. Specifically, the task is to translate questions from the
TruthfulQA test suite, where an adversarial prompt is prepended to the
questions, instructing the system to ignore the translation instruction and
answer the questions instead.
  In this test suite, we extend this approach to all the language pairs of the
WMT 2024 General Machine Translation task. Moreover, we include additional
attack formats in addition to the one originally studied.
