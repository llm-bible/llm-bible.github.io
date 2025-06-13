---
layout: publication
title: 'Positional Fragility In Llms: How Offset Effects Reshape Our Understanding Of Memorization Risks'
authors: Yixuan Xu, Antoni-joan Solergibert I Llaquet, Antoine Bosselut, Imanol Schlag
conference: "Arxiv"
year: 2025
bibkey: xu2025positional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13171"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Large language models are known to memorize parts of their training data, posing risk of copyright violations. To systematically examine this risk, we pretrain language models (1B/3B/8B) from scratch on 83B tokens, mixing web-scale data with public domain books used to simulate copyrighted content at controlled frequencies at lengths at least ten times longer than prior work. We thereby identified the offset effect, a phenomenon characterized by two key findings: (1) verbatim memorization is most strongly triggered by short prefixes drawn from the beginning of the context window, with memorization decreasing counterintuitively as prefix length increases; and (2) a sharp decline in verbatim recall when prefix begins offset from the initial tokens of the context window. We attribute this to positional fragility: models rely disproportionately on the earliest tokens in their context window as retrieval anchors, making them sensitive to even slight shifts. We further observe that when the model fails to retrieve memorized content, it often produces degenerated text. Leveraging these findings, we show that shifting sensitive data deeper into the context window suppresses both extractable memorization and degeneration. Our results suggest that positional offset is a critical and previously overlooked axis for evaluating memorization risks, since prior work implicitly assumed uniformity by probing only from the beginning of training sequences.
