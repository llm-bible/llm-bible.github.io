---
layout: publication
title: 'Information-guided Identification Of Training Data Imprint In (proprietary) Large Language Models'
authors: Abhilasha Ravichander, Jillian Fisher, Taylor Sorensen, Ximing Lu, Yuchen Lin, Maria Antoniak, Niloofar Mireshghallah, Chandra Bhagavatula, Yejin Choi
conference: "Arxiv"
year: 2025
bibkey: ravichander2025information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12072"}
tags: ['GPT', 'Ethics and Bias', 'Model Architecture', 'Interpretability', 'Training Techniques']
---
High-quality training data has proven crucial for developing performant large
language models (LLMs). However, commercial LLM providers disclose few, if any,
details about the data used for training. This lack of transparency creates
multiple challenges: it limits external oversight and inspection of LLMs for
issues such as copyright infringement, it undermines the agency of data
authors, and it hinders scientific research on critical issues such as data
contamination and data selection. How can we recover what training data is
known to LLMs? In this work, we demonstrate a new method to identify training
data known to proprietary LLMs like GPT-4 without requiring any access to model
weights or token probabilities, by using information-guided probes. Our work
builds on a key observation: text passages with high surprisal are good search
material for memorization probes. By evaluating a model's ability to
successfully reconstruct high-surprisal tokens in text, we can identify a
surprising number of texts memorized by LLMs.
