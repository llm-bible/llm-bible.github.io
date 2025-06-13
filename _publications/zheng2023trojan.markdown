---
layout: publication
title: 'Trojfsp: Trojan Insertion In Few-shot Prompt Tuning'
authors: Mengxin Zheng, Jiaqi Xue, Xun Chen, Yanshan Wang, Qian Lou, Lei Jiang
conference: "Arxiv"
year: 2023
bibkey: zheng2023trojan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10467"}
tags: ['Model Architecture', 'Security', 'Attention Mechanism', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Prompt tuning is one of the most effective solutions to adapting a fixed
pre-trained language model (PLM) for various downstream tasks, especially with
only a few input samples. However, the security issues, e.g., Trojan attacks,
of prompt tuning on a few data samples are not well-studied. Transferring
established data poisoning attacks directly to few-shot prompt tuning presents
multiple challenges. One significant issue is the \textit\{poisoned imbalance
issue\}, where non-target class samples are added to the target class, resulting
in a greater number of target-class samples compared to non-target class. While
this issue is not critical in regular tuning, it significantly hampers the
few-shot prompt tuning, making it difficult to simultaneously achieve a high
attack success rate (ASR) and maintain clean data accuracy (CDA). Additionally,
few-shot prompting is prone to overfitting in terms of both ASR and CDA. In
this paper, we introduce \textit\{TrojFSP\}, a method designed to address the
challenges. To solve the poisoned imbalance issue, we develop a
\textit\{Target-Class Shrink (TC-Shrink)\} technique, which aims to equalize the
number of poisoning samples. To combat overfitting, we employ a
\textit\{Selective Token Poisoning\} technique to boost attack performance.
Furthermore, we introduce a \textit\{Trojan-Trigger Attention\} objective
function to amplify the attention of the poisoned trojan prompt on triggers.
Experiments show that our TrojFSP achieves an ASR of over 99% while
maintaining negligible decreases in CDA across various PLMs and datasets.
