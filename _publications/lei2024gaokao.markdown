---
layout: publication
title: 'Gaokao-eval: Does High Scores Truly Reflect Strong Capabilities In Llms?'
authors: Zhikai Lei, Tianyi Liang, Hanglei Hu, Jin Zhang, Yunhua Zhou, Yunfan Shao, Linyang Li, Chenchui Li, Changbo Wang, Hang Yan, Qipeng Guo
conference: "Arxiv"
year: 2024
bibkey: lei2024gaokao
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10056"}
tags: ['Uncategorized']
---
Large Language Models (LLMs) are commonly evaluated using human-crafted
benchmarks, under the premise that higher scores implicitly reflect stronger
human-like performance. However, there is growing concern that LLMs may ``game"
these benchmarks due to data leakage, achieving high scores while struggling
with tasks simple for humans. To substantively address the problem, we create
GAOKAO-Eval, a comprehensive benchmark based on China's National College
Entrance Examination (Gaokao), and conduct ``closed-book" evaluations for
representative models released prior to Gaokao. Contrary to prevailing
consensus, even after addressing data leakage and comprehensiveness,
GAOKAO-Eval reveals that high scores still fail to truly reflect human-aligned
capabilities. To better understand this mismatch, We introduce the Rasch model
from cognitive psychology to analyze LLM scoring patterns and identify two key
discrepancies: 1) anomalous consistent performance across various question
difficulties, and 2) high variance in performance on questions of similar
difficulty. In addition, We identified inconsistent grading of LLM-generated
answers among teachers and recurring mistake patterns. we find that the
phenomenons are well-grounded in the motivations behind OpenAI o1, and o1's
reasoning-as-difficulties can mitigate the mismatch. These results show that
GAOKAO-Eval can reveal limitations in LLM capabilities not captured by current
benchmarks and highlight the need for more LLM-aligned difficulty analysis.
