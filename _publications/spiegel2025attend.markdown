---
layout: publication
title: 'Attend Or Perish: Benchmarking Attention In Algorithmic Reasoning'
authors: Michal Spiegel, Michal Štefánik, Marek Kadlčík, Josef Kuchař
conference: "Arxiv"
year: 2025
bibkey: spiegel2025attend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01909"}
  - {name: "Code", url: "https://github.com/michalspiegel/AttentionSpan"}
tags: ['Security', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Can transformers learn to perform algorithmic tasks reliably across
previously unseen input/output domains? While pre-trained language models show
solid accuracy on benchmarks incorporating algorithmic reasoning, assessing the
reliability of these results necessitates an ability to cleanse models'
functional capabilities from memorization. In this paper, we propose an
algorithmic benchmark comprising six tasks of infinite input domains where we
can also disentangle and trace the correct, robust algorithm necessary for the
task. This allows us to assess (i) models' ability to extrapolate to unseen
types of inputs, including new lengths, value ranges or input domains, but also
(ii) to assess the robustness of the functional mechanism in recent models
through the lens of their attention maps. We make the implementation of all our
tasks and interoperability methods publicly available at
https://github.com/michalspiegel/AttentionSpan .
