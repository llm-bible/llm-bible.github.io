---
layout: publication
title: 'Toxic Subword Pruning For Dialogue Response Generation On Large Language Models'
authors: Hongyuan Lu, Wai Lam
conference: "Arxiv"
year: 2024
bibkey: lu2024toxic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04155"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Applications']
---
How to defend large language models (LLMs) from generating toxic content is
an important research area. Yet, most research focused on various model
training techniques to remediate LLMs by updating their weights. A typical
related research area is safety alignment. This however is often costly and
tedious and can expose the model to even more problems such as catastrophic
forgetting if the trainings are not carefully handled by experienced NLP
practitioners. We thus propose a simple yet effective and novel algorithm,
namely \textbf\{Tox\}ic Subword \textbf\{Prun\}ing (ToxPrune) to prune the subword
contained by the toxic words from BPE in trained LLMs. In contrast to the
previous work that demonstrates pruning BPE tokens as harmful to the task of
machine translation, we surprisingly found its usefulness in preventing toxic
content from being generated on LLMs. Fortunately, our findings suggest that
ToxPrune simultaneously improves the toxic language model NSFW-3B on the task
of dialogue response generation obviously. We surprisingly found that ToxPrune
can even obviously improve official Llama-3.1-6B in the metric of dialogue
diversity. Extensive automatic results and human evaluation indicate that
ToxPrune could be helpful for both remediating toxic LLMs and improving
non-toxic LLMs on the task of dialogue response generation.\footnote\{We plan to
release the resources to facilitate future work.\}
