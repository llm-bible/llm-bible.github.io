---
layout: publication
title: 'Human-in-the-loop Generation Of Adversarial Texts: A Case Study On Tibetan Script'
authors: Xi Cao, Yuan Sun, Jiajun Li, Quzong Gesang, Nuo Qun, Tashi Nyima
conference: "Arxiv"
year: 2024
bibkey: cao2024human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12478"}
tags: ['Security']
---
DNN-based language models perform excellently on various tasks, but even SOTA
LLMs are susceptible to textual adversarial attacks. Adversarial texts play
crucial roles in multiple subfields of NLP. However, current research has the
following issues. (1) Most textual adversarial attack methods target
rich-resourced languages. How do we generate adversarial texts for less-studied
languages? (2) Most textual adversarial attack methods are prone to generating
invalid or ambiguous adversarial texts. How do we construct high-quality
adversarial robustness benchmarks? (3) New language models may be immune to
part of previously generated adversarial texts. How do we update adversarial
robustness benchmarks? To address the above issues, we introduce HITL-GAT, a
system based on a general approach to human-in-the-loop generation of
adversarial texts. HITL-GAT contains four stages in one pipeline: victim model
construction, adversarial example generation, high-quality benchmark
construction, and adversarial robustness evaluation. Additionally, we utilize
HITL-GAT to make a case study on Tibetan script which can be a reference for
the adversarial research of other less-studied languages.
