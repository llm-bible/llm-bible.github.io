---
layout: publication
title: 'SCITAB: A Challenging Benchmark For Compositional Reasoning And Claim Verification On Scientific Tables'
authors: Lu Xinyuan, Pan Liangming, Liu Qian, Nakov Preslav, Kan Min-yen
conference: "Arxiv"
year: 2023
bibkey: lu2023challenging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13186"}
  - {name: "Code", url: "https://github.com/XinyuanLu00/SciTab"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Current scientific fact-checking benchmarks exhibit several shortcomings,
such as biases arising from crowd-sourced claims and an over-reliance on
text-based evidence. We present SCITAB, a challenging evaluation dataset
consisting of 1.2K expert-verified scientific claims that 1) originate from
authentic scientific publications and 2) require compositional reasoning for
verification. The claims are paired with evidence-containing scientific tables
annotated with labels. Through extensive evaluations, we demonstrate that
SCITAB poses a significant challenge to state-of-the-art models, including
table-based pretraining models and large language models. All models except
GPT-4 achieved performance barely above random guessing. Popular prompting
techniques, such as Chain-of-Thought, do not achieve much performance gains on
SCITAB. Our analysis uncovers several unique challenges posed by SCITAB,
including table grounding, claim ambiguity, and compositional reasoning. Our
codes and data are publicly available at https://github.com/XinyuanLu00/SciTab.
