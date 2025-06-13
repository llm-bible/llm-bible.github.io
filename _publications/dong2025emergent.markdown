---
layout: publication
title: 'Emergent Response Planning In LLM'
authors: Zhichen Dong, Zhanhui Zhou, Zhixuan Liu, Chao Yang, Chaochao Lu
conference: "Arxiv"
year: 2025
bibkey: dong2025emergent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06258"}
tags: ['Interpretability', 'Ethics and Bias', 'Prompting', 'Applications']
---
In this work, we argue that large language models (LLMs), though trained to
predict only the next token, exhibit emergent planning behaviors:
\\(\textbf\{their hidden representations encode future outputs beyond the next
token\}\\). Through simple probing, we demonstrate that LLM prompt representations
encode global attributes of their entire responses, including
\\(\textit\{structural attributes\}\\) (response length, reasoning steps),
\\(\textit\{content attributes\}\\) (character choices in storywriting,
multiple-choice answers at the end of response), and \\(\textit\{behavioral
attributes\}\\) (answer confidence, factual consistency). In addition to
identifying response planning, we explore how it scales with model size across
tasks and how it evolves during generation. The findings that LLMs plan ahead
for the future in their hidden representations suggests potential applications
for improving transparency and generation control.
