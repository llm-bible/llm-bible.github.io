---
layout: publication
title: 'KMMLU: Measuring Massive Multitask Language Understanding In Korean'
authors: Son Guijin, Lee Hanwool, Kim Sungdong, Kim Seungone, Muennighoff Niklas, Choi Taekyoon, Park Cheonbok, Yoo Kang Min, Biderman Stella
conference: "Arxiv"
year: 2024
bibkey: son2024measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11548"}
tags: ['GPT', 'Model Architecture', 'Uncategorized']
---
We propose KMMLU, a new Korean benchmark with 35,030 expert-level
multiple-choice questions across 45 subjects ranging from humanities to STEM.
While prior Korean benchmarks are translated from existing English benchmarks,
KMMLU is collected from original Korean exams, capturing linguistic and
cultural aspects of the Korean language. We test 27 public and proprietary LLMs
and observe the best public model to score 50.5%, leaving significant room for
improvement. This model was primarily trained for English and Chinese, not
Korean. Current LLMs tailored to Korean, such as Polyglot-Ko, perform far
worse. Surprisingly, even the most capable proprietary LLMs, e.g., GPT-4 and
HyperCLOVA X do not exceed 60%. This suggests that further work is needed to
improve LLMs for Korean, and we believe KMMLU offers the appropriate tool to
track this progress. We make our dataset publicly available on the Hugging Face
Hub and integrate the benchmark into EleutherAI's Language Model Evaluation
Harness.
