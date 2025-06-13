---
layout: publication
title: 'Focus On This, Not That! Steering Llms With Adaptive Feature Specification'
authors: Tom A. Lamb, Adam Davies, Alasdair Paren, Philip H. S. Torr, Francesco Pinto
conference: "Arxiv"
year: 2024
bibkey: lamb2024focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22944"}
tags: ['Ethics and Bias', 'Security', 'Training Techniques', 'RAG']
---
Despite the success of Instruction Tuning (IT) in training large language models (LLMs), such models often leverage spurious or biased features learnt from their training data and can become misaligned, leading to undesired behaviours. While existing techniques can steer model behaviour at inference-time, they are often post-hoc and do not embed steering as an intrinsic model feature. In this work, we introduce Focus Instruction Tuning (FIT), which trains LLMs to condition their responses by focusing on specific features whilst ignoring others, leading to different behaviours based on what features are specified. Across diverse benchmarks, we demonstrate that FIT: (i) successfully steers behaviour at inference time; (ii) increases robustness by amplifying core task signals and down-weighting spurious cues; (iii) mitigates social bias by suppressing demographic attributes; and (iv) generalises under distribution shifts and to previously unseen focus features. FIT therefore offers a lightweight, intrinsic mechanism for building more robust, fair, and easily controllable LLMs.
