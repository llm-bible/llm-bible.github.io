---
layout: publication
title: 'REAL Sampling: Boosting Factuality And Diversity Of Open-ended Generation Via Asymptotic Entropy'
authors: Haw-shiuan Chang, Nanyun Peng, Mohit Bansal, Anil Ramakrishna, Tagyoung Chung
conference: "Arxiv"
year: 2024
bibkey: chang2024real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07735"}
tags: ['Prompting']
---
Decoding methods for large language models (LLMs) usually struggle with the
tradeoff between ensuring factuality and maintaining diversity. For example, a
higher p threshold in the nucleus (top-p) sampling increases the diversity but
decreases the factuality, and vice versa. In this paper, we propose REAL
(Residual Entropy from Asymptotic Line) sampling, a decoding method that
achieves improved factuality and diversity over nucleus sampling by predicting
an adaptive threshold of \\(p\\). Specifically, REAL sampling predicts the
step-wise likelihood of an LLM to hallucinate, and lowers the p threshold when
an LLM is likely to hallucinate. Otherwise, REAL sampling increases the p
threshold to boost the diversity. To predict the step-wise hallucination
likelihood without supervision, we construct a Token-level Hallucination
Forecasting (THF) model to predict the asymptotic entropy (i.e., inherent
uncertainty) of the next token by extrapolating the next-token entropies from a
series of LLMs with different sizes. If a LLM's entropy is higher than the
asymptotic entropy (i.e., the LLM is more uncertain than it should be), the THF
model predicts a high hallucination hazard, which leads to a lower p threshold
in REAL sampling. In the FactualityPrompts benchmark, we demonstrate that REAL
sampling based on a 70M THF model can substantially improve the factuality and
diversity of 7B LLMs simultaneously, judged by both retrieval-based metrics and
human evaluation. After combined with contrastive decoding, REAL sampling
outperforms 9 sampling methods, and generates texts that are more factual than
the greedy sampling and more diverse than the nucleus sampling with \\(p=0.5\\).
Furthermore, the predicted asymptotic entropy is also a useful unsupervised
signal for hallucination detection tasks.
