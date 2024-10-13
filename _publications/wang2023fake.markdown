---
layout: publication
title: 'Fake Alignment: Are Llms Really Aligned Well?'
authors: Wang Yixu, Teng Yan, Huang Kexin, Lyu Chengqi, Zhang Songyang, Zhang Wenwei, Ma Xingjun, Jiang Yu-gang, Qiao Yu, Wang Yingchun
conference: "Arxiv"
year: 2023
bibkey: wang2023fake
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05915"}
  - {name: "Code", url: "https://github.com/AIFlames/Fake-Alignment"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
The growing awareness of safety concerns in large language models (LLMs) has
sparked considerable interest in the evaluation of safety. This study
investigates an under-explored issue about the evaluation of LLMs, namely the
substantial discrepancy in performance between multiple-choice questions and
open-ended questions. Inspired by research on jailbreak attack patterns, we
argue this is caused by mismatched generalization. That is, LLM only remembers
the answer style for open-ended safety questions, which makes it unable to
solve other forms of safety tests. We refer to this phenomenon as fake
alignment and construct a comparative benchmark to empirically verify its
existence in LLMs. We introduce a Fake alIgNment Evaluation (FINE) framework
and two novel metrics--Consistency Score (CS) and Consistent Safety Score
(CSS), which jointly assess two complementary forms of evaluation to quantify
fake alignment and obtain corrected performance estimation. Applying FINE to 14
widely-used LLMs reveals several models with purported safety are poorly
aligned in practice. Subsequently, we found that multiple-choice format data
can also be used as high-quality contrast distillation-based fine-tuning data,
which can strongly improve the alignment consistency of LLMs with minimal
fine-tuning overhead. For data and code, see
https://github.com/AIFlames/Fake-Alignment.
