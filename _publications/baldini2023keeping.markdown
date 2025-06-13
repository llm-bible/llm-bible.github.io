---
layout: publication
title: 'Keeping Up With The Language Models: Systematic Benchmark Extension For Bias Auditing'
authors: Ioana Baldini, Chhavi Yadav, Manish Nagireddy, Payel Das, Kush R. Varshney
conference: "Arxiv"
year: 2023
bibkey: baldini2023keeping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12620"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Bias auditing of language models (LMs) has received considerable attention as
LMs are becoming widespread. As such, several benchmarks for bias auditing have
been proposed. At the same time, the rapid evolution of LMs can make these
benchmarks irrelevant in no time. Bias auditing is further complicated by LM
brittleness: when a presumably biased outcome is observed, is it due to model
bias or model brittleness? We propose enlisting the models themselves to help
construct bias auditing datasets that remain challenging, and introduce bias
measures that distinguish between different types of model errors. First, we
extend an existing bias benchmark for NLI (BBNLI) using a combination of
LM-generated lexical variations, adversarial filtering, and human validation.
We demonstrate that the newly created dataset BBNLI-next is more challenging
than BBNLI: on average, BBNLI-next reduces the accuracy of state-of-the-art NLI
models from 95.3%, as observed by BBNLI, to a strikingly low 57.5%. Second, we
employ BBNLI-next to showcase the interplay between robustness and bias: we
point out shortcomings in current bias scores and propose bias measures that
take into account both bias and model brittleness. Third, despite the fact that
BBNLI-next was designed with non-generative models in mind, we show that the
new dataset is also able to uncover bias in state-of-the-art open-source
generative LMs.
  Note: All datasets included in this work are in English and they address
US-centered social biases. In the spirit of efficient NLP research, no model
training or fine-tuning was performed to conduct this research.
  Warning: This paper contains offensive text examples.
