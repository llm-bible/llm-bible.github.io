---
layout: publication
title: 'KV Prediction For Improved Time To First Token'
authors: Maxwell Horton, Qingqing Cao, Chenfan Sun, Yanzi Jin, Sachin Mehta, Mohammad Rastegari, Moin Nabi
conference: "Arxiv"
year: 2024
bibkey: horton2024kv
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.08391'}
  - {name: "Code", url: 'https://github.com/apple/corenet/tree/main/projects/kv-prediction'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
Inference with transformer-based language models begins with a prompt
processing step. In this step, the model generates the first output token and
stores the KV cache needed for future generation steps. This prompt processing
step can be computationally expensive, taking 10s of seconds or more for
billion-parameter models on edge devices when prompt lengths or batch sizes
rise. This degrades user experience by introducing significant latency into the
model's outputs. To reduce the time spent producing the first output (known as
the ``time to first token'', or TTFT) of a pretrained model, we introduce a
novel method called KV Prediction. In our method, a small auxiliary model is
used to process the prompt and produce an approximation of the KV cache used by
a base model. This approximated KV cache is then used with the base model for
autoregressive generation without the need to query the auxiliary model again.
We demonstrate that our method produces a pareto-optimal efficiency-accuracy
trade-off when compared to baselines. On TriviaQA, we demonstrate relative
accuracy improvements in the range of \\(15%-50%\\) across a range of TTFT FLOPs
budgets. We also demonstrate accuracy improvements of up to \\(30%\\) on HumanEval
python code completion at fixed TTFT FLOPs budgets. Additionally, we benchmark
models on an Apple M2 Pro CPU and demonstrate that our improvement in FLOPs
translates to a TTFT speedup on hardware. We release our code at
https://github.com/apple/corenet/tree/main/projects/kv-prediction .
