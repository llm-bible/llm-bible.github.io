---
layout: publication
title: When Can LLMs Actually Correct Their Own Mistakes A Critical Survey of Self-Correction of LLMs
authors: Kamoi Ryo, Zhang Yusen, Zhang Nan, Han Jiawei, Zhang Rui
conference: "Arxiv"
year: 2024
bibkey: kamoi2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01297"}
tags: ['Arxiv', 'Pretraining Methods', 'Survey Paper', 'A']
---
Self-correction is an approach to improving responses from large language models (LLMs) by refining the responses using LLMs during inference. Prior work has proposed various self-correction frameworks using different sources of feedback including self-evaluation and external feedback. However there is still no consensus on the question of when LLMs can correct their own mistakes as recent studies also report negative results. In this work we critically survey broad papers and discuss the conditions required for successful self-correction. We first find that prior studies often do not define their research questions in detail and involve impractical frameworks or unfair evaluations that over-evaluate self-correction. To tackle these issues we categorize research questions in self-correction research and provide a checklist for designing appropriate experiments. Our critical survey based on the newly categorized research questions shows that (1) no prior work demonstrates successful self-correction with feedback from prompted LLMs except for studies in tasks that are exceptionally suited for self-correction (2) self-correction works well in tasks that can use reliable external feedback and (3) large-scale fine-tuning enables self-correction.
