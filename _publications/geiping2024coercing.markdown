---
layout: publication
title: 'Coercing Llms To Do And Reveal (almost) Anything'
authors: Jonas Geiping, Alex Stein, Manli Shu, Khalid Saifullah, Yuxin Wen, Tom Goldstein
conference: "Arxiv"
year: 2024
bibkey: geiping2024coercing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14020"}
tags: ['Training Techniques', 'Security', 'Pre-Training']
---
It has recently been shown that adversarial attacks on large language models
(LLMs) can "jailbreak" the model into making harmful statements. In this work,
we argue that the spectrum of adversarial attacks on LLMs is much larger than
merely jailbreaking. We provide a broad overview of possible attack surfaces
and attack goals. Based on a series of concrete examples, we discuss,
categorize and systematize attacks that coerce varied unintended behaviors,
such as misdirection, model control, denial-of-service, or data extraction.
  We analyze these attacks in controlled experiments, and find that many of
them stem from the practice of pre-training LLMs with coding capabilities, as
well as the continued existence of strange "glitch" tokens in common LLM
vocabularies that should be removed for security reasons.
