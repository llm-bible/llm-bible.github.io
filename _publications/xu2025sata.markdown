---
layout: publication
title: 'SATA-BENCH: Select All That Apply Benchmark For Multiple Choice Questions'
authors: Weijie Xu, Shixian Cui, Xi Fang, Chi Xue, Stephanie Eckman, Chandan Reddy
conference: "Arxiv"
year: 2025
bibkey: xu2025sata
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00643'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Applications', 'Tools']
---
Large language models (LLMs) are increasingly evaluated on single-answer multiple-choice tasks, yet many real-world problems require identifying all correct answers from a set of options. This capability remains underexplored. We introduce SATA-BENCH, the first dedicated benchmark for evaluating LLMs on Select All That Apply (SATA) questions across diverse domains, including reading comprehension, law, and biomedicine. Our evaluation of 27 open-source and proprietary models reveals a significant gap: even the strongest model achieves only 41.8% exact match, exposing LLMs' inability to reliably identify all correct answers. We find that this weakness stems from two core challenges: selection bias - models favor certain choices regardless of content, and count bias - models fail to predict the correct number of answers. To address these issues, we propose Choice Funnel, a decoding strategy that combines token debiasing with adaptive thresholding to guide models toward complete and accurate selections. Choice Funnel achieves up to 29% higher exact match than competitive baselines while reducing inference cost by over 64%. Our findings expose fundamental limitations in current LLMs and introduce a new framework for diagnosing and improving multi-answer reasoning. We release SATA-BENCH and Choice Funnel to promote LLM development for robust decision-making in realistic, multi-answer applications.
