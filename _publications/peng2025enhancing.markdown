---
layout: publication
title: 'Enhancing Input-label Mapping In In-context Learning With Contrastive Decoding'
authors: Keqin Peng, Liang Ding, Yuanxin Ouyang, Meng Fang, Yancheng Yuan, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: peng2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13738"}
tags: ['RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) excel at a range of tasks through in-context
learning (ICL), where only a few task examples guide their predictions.
However, prior research highlights that LLMs often overlook input-label mapping
information in ICL, relying more on their pre-trained knowledge. To address
this issue, we introduce In-Context Contrastive Decoding (ICCD), a novel method
that emphasizes input-label mapping by contrasting the output distributions
between positive and negative in-context examples. Experiments on 7 natural
language understanding (NLU) tasks show that our ICCD method brings consistent
and significant improvement (up to +2.1 improvement on average) upon 6
different scales of LLMs without requiring additional training. Our approach is
versatile, enhancing performance with various demonstration selection methods,
demonstrating its broad applicability and effectiveness. The code and scripts
will be publicly released.
