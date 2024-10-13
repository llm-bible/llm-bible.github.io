---
layout: publication
title: 'A Closer Look Into Automatic Evaluation Using Large Language Models'
authors: Chiang Cheng-han, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: chiang2023closer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05657"}
tags: ['GPT', 'Model Architecture', 'Uncategorized']
---
Using large language models (LLMs) to evaluate text quality has recently
gained popularity. Some prior works explore the idea of using LLMs for
evaluation, while they differ in some details of the evaluation process. In
this paper, we analyze LLM evaluation (Chiang and Lee, 2023) and G-Eval (Liu et
al., 2023), and we discuss how those details in the evaluation process change
how well the ratings given by LLMs correlate with human ratings. We find that
the auto Chain-of-Thought (CoT) used in G-Eval does not always make G-Eval more
aligned with human ratings. We also show that forcing the LLM to output only a
numeric rating, as in G-Eval, is suboptimal. Last, we reveal that asking the
LLM to explain its own ratings consistently improves the correlation between
the ChatGPT and human ratings and pushes state-of-the-art (SoTA) correlations
on two meta-evaluation datasets.
