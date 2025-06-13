---
layout: publication
title: 'Dissociation Of Faithful And Unfaithful Reasoning In Llms'
authors: Evelyn Yee, Alice Li, Chenyu Tang, Yeon Ho Jung, Ramamohan Paturi, Leon Bergen
conference: "Arxiv"
year: 2024
bibkey: yee2024dissociation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15092"}
tags: ['Interpretability and Explainability']
---
Large language models (LLMs) often improve their performance in downstream
tasks when they generate Chain of Thought reasoning text before producing an
answer. We investigate how LLMs recover from errors in Chain of Thought.
Through analysis of error recovery behaviors, we find evidence for
unfaithfulness in Chain of Thought, which occurs when models arrive at the
correct answer despite invalid reasoning text. We identify factors that shift
LLM recovery behavior: LLMs recover more frequently from obvious errors and in
contexts that provide more evidence for the correct answer. Critically, these
factors have divergent effects on faithful and unfaithful recoveries. Our
results indicate that there are distinct mechanisms driving faithful and
unfaithful error recoveries. Selective targeting of these mechanisms may be
able to drive down the rate of unfaithful reasoning and improve model
interpretability.
