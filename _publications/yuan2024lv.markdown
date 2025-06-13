---
layout: publication
title: 'Lv-eval: A Balanced Long-context Benchmark With 5 Length Levels Up To 256K'
authors: Tao Yuan, Xuefei Ning, Dong Zhou, Zhijie Yang, Shiyao Li, Minghui Zhuang, Zheyue Tan, Zhuyu Yao, Dahua Lin, Boxun Li, Guohao Dai, Shengen Yan, Yu Wang
conference: "Arxiv"
year: 2024
bibkey: yuan2024lv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05136"}
  - {name: "Code", url: "https://github.com/infinigence/LVEval"}
tags: ['RAG', 'Has Code', 'Ethics and Bias', 'Reinforcement Learning']
---
State-of-the-art large language models (LLMs) are now claiming remarkable
supported context lengths of 256k or even more. In contrast, the average
context lengths of mainstream benchmarks are insufficient (5k-21k), and they
suffer from potential knowledge leakage and inaccurate metrics, resulting in
biased evaluation. This paper introduces LV-Eval, a challenging long-context
benchmark with five length levels (16k, 32k, 64k, 128k, and 256k) reaching up
to 256k words. LV-Eval features two main tasks, single-hop QA and multi-hop QA,
comprising 11 bilingual datasets. The design of LV-Eval has incorporated three
key techniques, namely confusing facts insertion, keyword and phrase
replacement, and keyword-recall-based metric design. The advantages of LV-Eval
include controllable evaluation across different context lengths, challenging
test instances with confusing facts, mitigated knowledge leakage, and more
objective evaluations. We evaluate 15 LLMs on LV-Eval and conduct ablation
studies on the benchmarking techniques. The results reveal that: (i)
Moonshot-v1 and recent large-scale open-source models, such as Qwen-2.5-72B and
Llama-3.1-70B, achieve the highest performance on LV-Eval, particularly at
lengths below 64k. (ii) Models exhibit distinct score trends. For example,
GLM-4-9B-128k, Yi-6B-200k, and Llama3-8B-1M exhibit a relatively gentle
degradation of performance, but their absolute performances may not necessarily
be higher than those of LLMs with shorter context lengths. (iii) LLMs'
performances can significantly degrade in the presence of confusing
information, especially in the pressure test of "needle in a haystack". (iv)
Issues related to knowledge leakage and inaccurate metrics introduce bias in
evaluation, and these concerns are alleviated in LV-Eval. All datasets and
evaluation codes are released at: https://github.com/infinigence/LVEval.
