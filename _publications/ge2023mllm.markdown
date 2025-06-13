---
layout: publication
title: 'Mllm-bench: Evaluating Multimodal Llms With Per-sample Criteria'
authors: Wentao Ge, Shunian Chen, Guiming Hardy Chen, Junying Chen, Zhihong Chen, Nuo Chen, Wenya Xie, Shuo Yan, Chenghao Zhu, Ziyue Lin, Song Dingjie, Xidong Wang, Anningzhe Gao, Zhang Zhiyi, Jianquan Li, Xiang Wan, Benyou Wang
conference: "Arxiv"
year: 2023
bibkey: ge2023mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13951"}
tags: ['Tools', 'Multimodal Models', 'Applications', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs) have broadened the scope of AI
applications. Existing automatic evaluation methodologies for MLLMs are mainly
limited in evaluating queries without considering user experiences,
inadequately addressing the nuances of creative and associative multimodal
tasks. However, the open-ended and subjective nature of such tasks poses a
significant challenge to the evaluation methodology, where it is difficult to
define the ground-truth answers for them. To this end, in our paper, we propose
a new evaluation paradigm for MLLMs, which is evaluating MLLMs with per-sample
criteria using potent MLLM as the judge. To validate the feasibility and
effectiveness of this paradigm, we design a benchmark, dubbed MLLM-Bench, by
curating the evaluation samples across six comprehensive cognitive levels. We
benchmark 21 popular MLLMs in a pairwise-comparison fashion, showing diverse
performance across models. Moreover, the validity of our benchmark manifests
itself in reaching 88.02% agreement with human evaluation. We contend that the
proposed paradigm explores the potential of MLLMs as effective evaluation tools
with the help of per-sample criteria. See online leaderboard at
\url\{https://mllm-bench.llmzoo.com\}.
