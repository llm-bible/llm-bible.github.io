---
layout: publication
title: 'Unraveling And Mitigating Safety Alignment Degradation Of Vision-language Models'
authors: Qin Liu, Chao Shang, Ling Liu, Nikolaos Pappas, Jie Ma, Neha Anna John, Srikanth Doss, Lluis Marquez, Miguel Ballesteros, Yassine Benajiba
conference: "Arxiv"
year: 2024
bibkey: liu2024unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09047"}
tags: ['Responsible AI', 'Training Techniques', 'Multimodal Models', 'Tools']
---
The safety alignment ability of Vision-Language Models (VLMs) is prone to be
degraded by the integration of the vision module compared to its LLM backbone.
We investigate this phenomenon, dubbed as ''safety alignment degradation'' in
this paper, and show that the challenge arises from the representation gap that
emerges when introducing vision modality to VLMs. In particular, we show that
the representations of multi-modal inputs shift away from that of text-only
inputs which represent the distribution that the LLM backbone is optimized for.
At the same time, the safety alignment capabilities, initially developed within
the textual embedding space, do not successfully transfer to this new
multi-modal representation space. To reduce safety alignment degradation, we
introduce Cross-Modality Representation Manipulation (CMRM), an inference time
representation intervention method for recovering the safety alignment ability
that is inherent in the LLM backbone of VLMs, while simultaneously preserving
the functional capabilities of VLMs. The empirical results show that our
framework significantly recovers the alignment ability that is inherited from
the LLM backbone with minimal impact on the fluency and linguistic capabilities
of pre-trained VLMs even without additional training. Specifically, the unsafe
rate of LLaVA-7B on multi-modal input can be reduced from 61.53% to as low as
3.15% with only inference-time intervention.
  WARNING: This paper contains examples of toxic or harmful language.
