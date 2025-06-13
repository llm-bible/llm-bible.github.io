---
layout: publication
title: 'Truthprint: Mitigating LVLM Object Hallucination Via Latent Truthful-guided Pre-intervention'
authors: Jinhao Duan, Fei Kong, Hao Cheng, James Diffenderfer, Bhavya Kailkhura, Lichao Sun, Xiaofeng Zhu, Xiaoshuang Shi, Kaidi Xu
conference: "Arxiv"
year: 2025
bibkey: duan2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10602"}
  - {name: "Code", url: "https://github.com/jinhaoduan/TruthPrInt"}
tags: ['Fine-Tuning', 'Multimodal Models', 'Has Code']
---
Object Hallucination (OH) has been acknowledged as one of the major
trustworthy challenges in Large Vision-Language Models (LVLMs). Recent
advancements in Large Language Models (LLMs) indicate that internal states,
such as hidden states, encode the "overall truthfulness" of generated
responses. However, it remains under-explored how internal states in LVLMs
function and whether they could serve as "per-token" hallucination indicators,
which is essential for mitigating OH. In this paper, we first conduct an
in-depth exploration of LVLM internal states in relation to OH issues and
discover that (1) LVLM internal states are high-specificity per-token
indicators of hallucination behaviors. Moreover, (2) different LVLMs encode
universal patterns of hallucinations in common latent subspaces, indicating
that there exist "generic truthful directions" shared by various LVLMs. Based
on these discoveries, we propose Truthful-Guided Pre-Intervention (TruthPrInt)
that first learns the truthful direction of LVLM decoding and then applies
truthful-guided inference-time intervention during LVLM decoding. We further
propose ComnHallu to enhance both cross-LVLM and cross-data hallucination
detection transferability by constructing and aligning hallucination latent
subspaces. We evaluate TruthPrInt in extensive experimental settings, including
in-domain and out-of-domain scenarios, over popular LVLMs and OH benchmarks.
Experimental results indicate that TruthPrInt significantly outperforms
state-of-the-art methods. Codes will be available at
https://github.com/jinhaoduan/TruthPrInt.
