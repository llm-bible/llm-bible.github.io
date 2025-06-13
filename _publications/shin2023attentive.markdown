---
layout: publication
title: 'An Attentive Inductive Bias For Sequential Recommendation Beyond The Self-attention'
authors: Yehjin Shin, Jeongwhan Choi, Hyowon Wi, Noseong Park
conference: "Arxiv"
year: 2023
bibkey: shin2023attentive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10325"}
  - {name: "Code", url: "https://github.com/yehjin-shin/BSARec"}
tags: ['Transformer', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Sequential recommendation (SR) models based on Transformers have achieved
remarkable successes. The self-attention mechanism of Transformers for computer
vision and natural language processing suffers from the oversmoothing problem,
i.e., hidden representations becoming similar to tokens. In the SR domain, we,
for the first time, show that the same problem occurs. We present pioneering
investigations that reveal the low-pass filtering nature of self-attention in
the SR, which causes oversmoothing. To this end, we propose a novel method
called \\(\textbf\{B\}\\)eyond \\(\textbf\{S\}\\)elf-\\(\textbf\{A\}\\)ttention for Sequential
\\(\textbf\{Rec\}\\)ommendation (BSARec), which leverages the Fourier transform to i)
inject an inductive bias by considering fine-grained sequential patterns and
ii) integrate low and high-frequency information to mitigate oversmoothing. Our
discovery shows significant advancements in the SR domain and is expected to
bridge the gap for existing Transformer-based SR models. We test our proposed
approach through extensive experiments on 6 benchmark datasets. The
experimental results demonstrate that our model outperforms 7 baseline methods
in terms of recommendation performance. Our code is available at
https://github.com/yehjin-shin/BSARec.
