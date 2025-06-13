---
layout: publication
title: 'RTP-LX: Can Llms Evaluate Toxicity In Multilingual Scenarios?'
authors: Adrian De Wynter, Ishaan Watts, Tua Wongsangaroonsri, Minghui Zhang, Noura Farra, Nektar Ege Altıntoprak, Lena Baur, Samantha Claudet, Pavel Gajdusek, Can Gören, Qilong Gu, Anna Kaminska, Tomasz Kaminski, Ruby Kuo, Akiko Kyuba, Jongho Lee, Kartik Mathur, Petter Merok, Ivana Milovanović, Nani Paananen, Vesa-matti Paananen, Anna Pavlenko, Bruno Pereira Vidal, Luciano Strika, Yueh Tsao, Davide Turcato, Oleksandr Vakhno, Judit Velcsov, Anna Vickers, Stéphanie Visser, Herdyan Widarmanto, Andrey Zaikin, Si-qing Chen
conference: "Arxiv"
year: 2024
bibkey: dewynter2024rtp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14397"}
tags: ['Responsible AI', 'Ethics and Bias', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) and small language models (SLMs) are being
adopted at remarkable speed, although their safety still remains a serious
concern. With the advent of multilingual S/LLMs, the question now becomes a
matter of scale: can we expand multilingual safety evaluations of these models
with the same velocity at which they are deployed? To this end, we introduce
RTP-LX, a human-transcreated and human-annotated corpus of toxic prompts and
outputs in 28 languages. RTP-LX follows participatory design practices, and a
portion of the corpus is especially designed to detect culturally-specific
toxic language. We evaluate 10 S/LLMs on their ability to detect toxic content
in a culturally-sensitive, multilingual scenario. We find that, although they
typically score acceptably in terms of accuracy, they have low agreement with
human judges when scoring holistically the toxicity of a prompt; and have
difficulty discerning harm in context-dependent scenarios, particularly with
subtle-yet-harmful content (e.g. microaggressions, bias). We release this
dataset to contribute to further reduce harmful uses of these models and
improve their safe deployment.
