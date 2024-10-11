---
layout: publication
title: 'Towards Achieving Human Parity On End-to-end Simultaneous Speech Translation Via LLM Agent'
authors: Cheng Shanbo, Huang Zhichao, Ko Tom, Li Hang, Peng Ningxin, Xu Lu, Zhang Qini
conference: "Arxiv"
year: 2024
bibkey: cheng2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21646"}
tags: ['Agentic', 'Reinforcement Learning', 'Uncategorized']
---
In this paper, we present Cross Language Agent -- Simultaneous Interpretation, CLASI, a high-quality and human-like Simultaneous Speech Translation (SiST) System. Inspired by professional human interpreters, we utilize a novel data-driven read-write strategy to balance the translation quality and latency. To address the challenge of translating in-domain terminologies, CLASI employs a multi-modal retrieving module to obtain relevant information to augment the translation. Supported by LLMs, our approach can generate error-tolerated translation by considering the input audio, historical context, and retrieved information. Experimental results show that our system outperforms other systems by significant margins. Aligned with professional human interpreters, we evaluate CLASI with a better human evaluation metric, valid information proportion (VIP), which measures the amount of information that can be successfully conveyed to the listeners. In the real-world scenarios, where the speeches are often disfluent, informal, and unclear, CLASI achieves VIP of 81.3&#37; and 78.0&#37; for Chinese-to-English and English-to-Chinese translation directions, respectively. In contrast, state-of-the-art commercial or open-source systems only achieve 35.4&#37; and 41.6&#37;. On the extremely hard dataset, where other systems achieve under 13&#37; VIP, CLASI can still achieve 70&#37; VIP.
