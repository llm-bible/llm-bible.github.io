---
layout: publication
title: 'Elitr-bench: A Meeting Assistant Benchmark For Long-context Language Models'
authors: Thibaut Thonet, Jos Rozen, Laurent Besacier
conference: "Arxiv"
year: 2024
bibkey: thonet2024elitr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.20262'}
tags: ['INTERSPEECH', 'Security', 'Model Architecture', 'Applications', 'GPT', 'Reinforcement Learning']
---
Research on Large Language Models (LLMs) has recently witnessed an increasing
interest in extending the models' context size to better capture dependencies
within long documents. While benchmarks have been proposed to assess long-range
abilities, existing efforts primarily considered generic tasks that are not
necessarily aligned with real-world applications. In contrast, we propose a new
benchmark for long-context LLMs focused on a practical meeting assistant
scenario in which the long contexts consist of transcripts obtained by
automatic speech recognition, presenting unique challenges for LLMs due to the
inherent noisiness and oral nature of such data. Our benchmark, ELITR-Bench,
augments the existing ELITR corpus by adding 271 manually crafted questions
with their ground-truth answers, as well as noisy versions of meeting
transcripts altered to target different Word Error Rate levels. Our experiments
with 12 long-context LLMs on ELITR-Bench confirm the progress made across
successive generations of both proprietary and open models, and point out their
discrepancies in terms of robustness to transcript noise. We also provide a
thorough analysis of our GPT-4-based evaluation, including insights from a
crowdsourcing study. Our findings indicate that while GPT-4's scores align with
human judges, its ability to distinguish beyond three score levels may be
limited.
