---
layout: publication
title: 'Improving Weak-to-strong Generalization With Reliability-aware Alignment'
authors: Yue Guo, Yi Yang
conference: "Arxiv"
year: 2024
bibkey: guo2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19032"}
  - {name: "Code", url: "http://github.com/Irenehere/ReliableAlignment"}
tags: ['Tools', 'Has Code']
---
Large language models (LLMs) are now rapidly advancing and surpassing human
abilities on many natural language tasks. However, aligning these super-human
LLMs with human knowledge remains challenging because the supervision signals
from human annotators may be wrong. This issue, known as the "super-alignment"
problem, requires enhancing weak-to-strong generalization, where a strong LLM
must generalize from imperfect supervision provided by a weaker source. To
address this issue, we propose an approach to improve weak-to-strong
generalization by involving the reliability of weak supervision signals in the
alignment process. In our method, we query the weak supervisor for multiple
answers, estimate the answer reliability, and enhance the alignment process by
filtering out uncertain data or re-weighting reliable data. Experiments on four
datasets demonstrate that our methods effectively identify the quality of weak
labels and significantly enhance weak-to-strong generalization. Our work
presents effective techniques for error-robust model alignment, reducing error
propagation from noisy supervision and enhancing the accuracy and reliability
of LLMs. Codes are publicly available at
http://github.com/Irenehere/ReliableAlignment.
