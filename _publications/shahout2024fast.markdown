---
layout: publication
title: 'Fast Inference For Augmented Large Language Models'
authors: Rana Shahout, Cong Liang, Shiji Xin, Qianru Lao, Yong Cui, Minlan Yu, Michael Mitzenmacher
conference: "Arxiv"
year: 2024
bibkey: shahout2024fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18248'}
tags: ['Efficiency and Optimization', 'Applications', 'Tools']
---
Augmented Large Language Models (LLMs) enhance the capabilities of standalone
LLMs by integrating external data sources through API calls. In interactive LLM
applications, efficient scheduling is crucial for maintaining low request
completion times, directly impacting user engagement. However, these
augmentations introduce scheduling challenges due to the need to manage limited
memory for cached information (KV caches). As a result, traditional size-based
scheduling algorithms, such as Shortest Job First (SJF), become less effective
at minimizing completion times. Existing work focuses only on handling requests
during API calls by preserving, discarding, or swapping memory without
considering how to schedule requests with API calls. In this paper, we propose
LAMPS, a novel LLM inference framework for augmented LLMs. LAMPS minimizes
request completion time through a unified scheduling approach that considers
the total length of requests and their handling strategies during API calls.
Recognizing that LLM inference is memory-bound, our approach ranks requests
based on their consumption of memory over time, which depends on both the
output sizes and how a request is managed during its API calls. To implement
our scheduling, LAMPS predicts the strategy that minimizes memory waste of a
request during its API calls, aligning with but improving upon existing
approaches. We also propose starvation prevention techniques and optimizations
to mitigate the overhead of our scheduling. We implement LAMPS on top of vLLM
and evaluate its performance against baseline LLM inference systems,
demonstrating improvements in end-to-end latency by 27%-85% and reductions in
TTFT by 4%-96% compared to the existing augmented-LLM system, with even greater
gains over vLLM.
