---
layout: publication
title: 'Cake: Circuit-aware Editing Enables Generalizable Knowledge Learners'
authors: Yunzhi Yao, Jizhan Fang, Jia-chen Gu, Ningyu Zhang, Shumin Deng, Huajun Chen, Nanyun Peng
conference: "Arxiv"
year: 2025
bibkey: yao2025circuit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16356"}
  - {name: "Code", url: "https://github.com/zjunlp/CaKE"}
tags: ['RAG', 'Has Code']
---
Knowledge Editing (KE) enables the modification of outdated or incorrect
information in large language models (LLMs). While existing KE methods can
update isolated facts, they struggle to generalize these updates to multi-hop
reasoning tasks that depend on the modified knowledge. Through an analysis of
reasoning circuits -- the neural pathways LLMs use for knowledge-based
inference, we observe that current layer-localized KE approaches, such as MEMIT
and WISE, which edit only single or a few model layers, struggle to effectively
incorporate updated information into these reasoning pathways. To address this
limitation, we propose CaKE (Circuit-aware Knowledge Editing), a novel method
that enables more effective integration of updated knowledge in LLMs. CaKE
leverages strategically curated data, guided by our circuits-based analysis,
that enforces the model to utilize the modified knowledge, stimulating the
model to develop appropriate reasoning circuits for newly integrated knowledge.
Experimental results show that CaKE enables more accurate and consistent use of
updated knowledge across related reasoning tasks, leading to an average of 20%
improvement in multi-hop reasoning accuracy on MQuAKE dataset compared to
existing KE methods. We release the code and data in
https://github.com/zjunlp/CaKE.
