---
layout: publication
title: Instruction Fine45;tuning Does Prompt Loss Matter
authors: Huerta-enochian Mathew, Ko Seung Yong
conference: "Arxiv"
year: 2024
bibkey: huertaenochian2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13586"}
tags: ['Prompting', 'Reinforcement Learning', 'Tools']
---
We present a novel study analyzing the effects of various prompt loss token weights (PLW) for supervised instruction fine45;tuning (SIFT). While prompt45;masking (PLW = 0) is common for SIFT some fine45;tuning APIs support fractional PLWs and suggest that using a small non45;zero PLW can help stabilize learning when fine45;tuning on short45;completion data. However there has never been a study confirming this claim and OpenAI a major cloud45;based SIFT provider recently removed this parameter from their fine45;tuning API. We found that performance of models fine45;tuned on short45;completion data had a statistically45;significant negative quadratic relationship with PLW. Using small values (0.01 45; 0.5) of PLW produced better results on multiple45;choice and short45;generation benchmarks (outperforming models fine45;tuned on long45;completion data) while large values (~ 1.0) of PLW produced better results on long45;generation benchmarks. We explained this effect and verified its importance through additional experiments. This research serves as a warning to API providers about the importance of providing a PLW parameter for SIFT.
