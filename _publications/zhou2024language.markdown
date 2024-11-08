---
layout: publication
title: 'Language-based User Profiles For Recommendation'
authors: Zhou Joyce, Dai Yijia, Joachims Thorsten
conference: "Arxiv"
year: 2024
bibkey: zhou2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15623"}
tags: ['Interpretability And Explainability', 'Reinforcement Learning']
---
Most conventional recommendation methods (e.g., matrix factorization)
represent user profiles as high-dimensional vectors. Unfortunately, these
vectors lack interpretability and steerability, and often perform poorly in
cold-start settings. To address these shortcomings, we explore the use of user
profiles that are represented as human-readable text. We propose the
Language-based Factorization Model (LFM), which is essentially an
encoder/decoder model where both the encoder and the decoder are large language
models (LLMs). The encoder LLM generates a compact natural-language profile of
the user's interests from the user's rating history. The decoder LLM uses this
summary profile to complete predictive downstream tasks. We evaluate our LFM
approach on the MovieLens dataset, comparing it against matrix factorization
and an LLM model that directly predicts from the user's rating history. In
cold-start settings, we find that our method can have higher accuracy than
matrix factorization. Furthermore, we find that generating a compact and
human-readable summary often performs comparably with or better than direct LLM
prediction, while enjoying better interpretability and shorter model input
length. Our results motivate a number of future research directions and
potential improvements.
