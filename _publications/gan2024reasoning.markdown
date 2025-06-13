---
layout: publication
title: 'Reasoning Robustness Of Llms To Adversarial Typographical Errors'
authors: Esther Gan, Yiran Zhao, Liying Cheng, Yancan Mao, Anirudh Goyal, Kenji Kawaguchi, Min-yen Kan, Michael Shieh
conference: "Arxiv"
year: 2024
bibkey: gan2024reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05345'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Security', 'Prompting']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in
reasoning using Chain-of-Thought (CoT) prompting. However, CoT can be biased by
users' instruction. In this work, we study the reasoning robustness of LLMs to
typographical errors, which can naturally occur in users' queries. We design an
Adversarial Typo Attack (\\(\texttt\{ATA\}\\)) algorithm that iteratively samples
typos for words that are important to the query and selects the edit that is
most likely to succeed in attacking. It shows that LLMs are sensitive to
minimal adversarial typographical changes. Notably, with 1 character edit,
Mistral-7B-Instruct's accuracy drops from 43.7% to 38.6% on GSM8K, while with 8
character edits the performance further drops to 19.2%. To extend our
evaluation to larger and closed-source LLMs, we develop the \\(\texttt\{R\\)^2\\(ATA\}\\)
benchmark, which assesses models' \\(\underline\{R\}\\)easoning
\\(\underline\{R\}\\)obustness to \\(\underline\{\texttt\{ATA\}\}\\). It includes adversarial
typographical questions derived from three widely used reasoning
datasets-GSM8K, BBH, and MMLU-by applying \\(\texttt\{ATA\}\\) to open-source LLMs.
\\(\texttt\{R\\)^2\\(ATA\}\\) demonstrates remarkable transferability and causes notable
performance drops across multiple super large and closed-source LLMs.
