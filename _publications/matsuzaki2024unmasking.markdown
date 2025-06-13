---
layout: publication
title: 'Unmasking The Limits Of Large Language Models: A Systematic Evaluation Of Masked Text Processing Ability Through Mskqa And Mskcal'
authors: Fuka Matsuzaki, Haru-tada Sato
conference: "Arxiv"
year: 2024
bibkey: matsuzaki2024unmasking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05665"}
tags: ['Model Architecture', 'GPT', 'Reinforcement Learning']
---
This paper sheds light on the limitations of Large Language Models (LLMs) by
rigorously evaluating their ability to process masked text. We introduce two
novel tasks: MskQA, measuring reasoning on masked question-answering datasets
like RealtimeQA, and MskCal, assessing numerical reasoning on masked arithmetic
problems.Testing GPT-4o and 4o-mini reveals that while LLMs exhibit some
resilience to masked text, their performance is highly contingent on masking
rates and semantic cues. Specifically, "solid masking," where semantic clues
are entirely absent, leads to a significant performance drop compared to
"partial lifting," where some semantic information is retained, indicating
LLMs' reliance on surface-level patterns. Interestingly, GPT-4o consistently
outperforms 4o-mini, particularly in MskCal, demonstrating a greater ability to
handle numerical reasoning with masked text. This underscores the crucial role
of semantic cues in the reasoning process of LLMs. Our study illuminates the
interplay between background knowledge and reasoning ability in masked text
processing, paving the way for a deeper understanding of LLM capabilities and
limitations, and highlighting the need for more robust evaluation methods to
accurately assess their true comprehension abilities.
