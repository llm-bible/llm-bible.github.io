---
layout: publication
title: 'Between Underthinking And Overthinking: An Empirical Study Of Reasoning Length And Correctness In Llms'
authors: Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie
conference: "Arxiv"
year: 2025
bibkey: su2025between
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00127'}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Merging']
---
Large language models (LLMs) are increasingly optimized for long reasoning,
under the assumption that more reasoning leads to better performance. However,
emerging evidence suggests that longer responses can sometimes degrade accuracy
rather than improve it. In this paper, we conduct a systematic empirical study
of the relationship between reasoning length and answer correctness. We find
that LLMs tend to overthink simple problems, generating unnecessarily long
outputs, and underthink harder ones, failing to extend their reasoning when it
is most needed. This indicates that models might misjudge problem difficulty
and fail to calibrate their response length appropriately. Furthermore, we
investigate the effects of length reduction with a preference optimization
algorithm when simply preferring the shorter responses regardless of answer
correctness. Experiments show that the generation length can be significantly
reduced while maintaining acceptable accuracy. Our findings highlight
generation length as a meaningful signal for reasoning behavior and motivate
further exploration into LLMs' self-awareness in reasoning length adaptation.
