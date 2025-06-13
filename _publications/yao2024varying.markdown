---
layout: publication
title: 'Varying Shades Of Wrong: Aligning Llms With Wrong Answers Only'
authors: Jihan Yao, Wenxuan Ding, Shangbin Feng, Lucy Lu Wang, Yulia Tsvetkov
conference: "Arxiv"
year: 2024
bibkey: yao2024varying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11055"}
tags: ['Efficiency and Optimization']
---
In the absence of abundant reliable annotations for challenging tasks and
contexts, how can we expand the frontier of LLM capabilities with potentially
wrong answers? We focus on two research questions: (1) Can LLMs generate
reliable preferences among wrong options? And if so, (2) Would alignment with
such wrong-over-wrong preferences be helpful? We employ methods based on
self-consistency, token probabilities, and LLM-as-a-judge to elicit
wrong-over-wrong preferences, and fine-tune language models with preference
optimization approaches using these synthesized preferences. Extensive
experiments with seven LLMs and eight datasets demonstrate that (1) LLMs do
have preliminary capability in distinguishing various shades of wrong,
achieving up to 20.9% higher performance than random guess; (2) Alignment with
wrong-over-wrong preferences helps LLMs to produce less wrong and sometimes
even outright correct answers, while overall improving model calibration.
