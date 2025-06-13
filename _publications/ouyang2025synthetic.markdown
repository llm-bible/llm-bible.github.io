---
layout: publication
title: 'Treecut: A Synthetic Unanswerable Math Word Problem Dataset For LLM Hallucination Evaluation'
authors: Jialin Ouyang
conference: "Arxiv"
year: 2025
bibkey: ouyang2025synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13442"}
  - {name: "Code", url: "https://github.com/j-bagel/treecut-math"}
tags: ['GPT', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) now achieve near-human performance on standard math word problem benchmarks (e.g., GSM8K), yet their true reasoning ability remains disputed. A key concern is that models often produce confident, yet unfounded, answers to unanswerable problems. We introduce TreeCut, a synthetic dataset that systematically generates infinite unanswerable math word problems and their answerable counterparts, by representing each question as a tree and removing chosen necessary conditions. Experiments show TreeCut effectively induce hallucinations in large language models, including GPT-4o and o3-mini, with rates of 64% and 44% in their respective worst-case scenarios under zero-shot setting. Further analysis highlights that deeper or more complex trees, composite item names, and removing necessary condition near the middle of a path all increase the likelihood of hallucinations, underscoring the persistent challenges LLMs face in identifying unanswerable math problems. The dataset generation code and sample data are available at https://github.com/j-bagel/treecut-math.
