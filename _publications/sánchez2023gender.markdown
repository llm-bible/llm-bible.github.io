---
layout: publication
title: 'Gender-specific Machine Translation With Large Language Models'
authors: Eduardo Sánchez, Pierre Andrews, Pontus Stenetorp, Mikel Artetxe, Marta R. Costa-jussà
conference: "Arxiv"
year: 2023
bibkey: sánchez2023gender
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03175"}
tags: ['RAG', 'Prompting', 'Ethics and Bias', 'Applications']
---
While machine translation (MT) systems have seen significant improvements, it
is still common for translations to reflect societal biases, such as gender
bias. Decoder-only Large Language Models (LLMs) have demonstrated potential in
MT, albeit with performance slightly lagging behind traditional encoder-decoder
Neural Machine Translation (NMT) systems. However, LLMs offer a unique
advantage: the ability to control the properties of the output through prompts.
In this study, we leverage this flexibility to explore LLaMa's capability to
produce gender-specific translations. Our results indicate that LLaMa can
generate gender-specific translations with translation accuracy and gender bias
comparable to NLLB, a state-of-the-art multilingual NMT system. Furthermore,
our experiments reveal that LLaMa's gender-specific translations rely on
coreference resolution to determine gender, showing higher gender variance in
gender-ambiguous datasets but maintaining consistency in less ambiguous
contexts. This research investigates the potential and challenges of using LLMs
for gender-specific translations as an instance of the controllability of
outputs offered by LLMs.
