---
layout: publication
title: 'INSIDE: Llms'' Internal States Retain The Power Of Hallucination Detection'
authors: Chao Chen, Kai Liu, Ze Chen, Yi Gu, Yue Wu, Mingyuan Tao, Zhihang Fu, Jieping Ye
conference: "Arxiv"
year: 2024
bibkey: chen2024internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03744"}
tags: ['Security']
---
Knowledge hallucination have raised widespread concerns for the security and
reliability of deployed LLMs. Previous efforts in detecting hallucinations have
been employed at logit-level uncertainty estimation or language-level
self-consistency evaluation, where the semantic information is inevitably lost
during the token-decoding procedure. Thus, we propose to explore the dense
semantic information retained within LLMs' \textbf\{IN\}ternal \textbf\{S\}tates
for halluc\textbf\{I\}nation \textbf\{DE\}tection (\textbf\{INSIDE\}). In particular,
a simple yet effective \textbf\{EigenScore\} metric is proposed to better
evaluate responses' self-consistency, which exploits the eigenvalues of
responses' covariance matrix to measure the semantic consistency/diversity in
the dense embedding space. Furthermore, from the perspective of self-consistent
hallucination detection, a test time feature clipping approach is explored to
truncate extreme activations in the internal states, which reduces
overconfident generations and potentially benefits the detection of
overconfident hallucinations. Extensive experiments and ablation studies are
performed on several popular LLMs and question-answering (QA) benchmarks,
showing the effectiveness of our proposal.
