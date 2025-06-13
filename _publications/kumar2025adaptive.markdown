---
layout: publication
title: 'HELIOS: Adaptive Model And Early-exit Selection For Efficient LLM Inference Serving'
authors: Avinash Kumar, Shashank Nag, Jason Clemons, Lizy John, Poulami Das
conference: "Arxiv"
year: 2025
bibkey: kumar2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10724"}
tags: ['Tools', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning']
---
Deploying large language models (LLMs) presents critical challenges due to
the inherent trade-offs associated with key performance metrics, such as
latency, accuracy, and throughput. Typically, gains in one metric is
accompanied with degradation in others. Early-Exit LLMs (EE-LLMs) efficiently
navigate this trade-off space by skipping some of the later model layers when
it confidently finds an output token early, thus reducing latency without
impacting accuracy. However, as the early exits taken depend on the task and
are unknown apriori to request processing, EE-LLMs conservatively load the
entire model, limiting resource savings and throughput. Also, current
frameworks statically select a model for a user task, limiting our ability to
adapt to changing nature of the input queries.
  We propose HELIOS to address these challenges. First, HELIOS shortlists a set
of candidate LLMs, evaluates them using a subset of prompts, gathering
telemetry data in real-time. Second, HELIOS uses the early exit data from these
evaluations to greedily load the selected model only up to a limited number of
layers. This approach yields memory savings which enables us to process more
requests at the same time, thereby improving throughput. Third, HELIOS monitors
and periodically reassesses the performance of the candidate LLMs and if
needed, switches to another model that can service incoming queries more
efficiently (such as using fewer layers without lowering accuracy). Our
evaluations show that HELIOS achieves 1.48\\(\times\\) throughput, 1.10\\(\times\\)
energy-efficiency, 1.39\\(\times\\) lower response time, and 3.7\\(\times\\)
improvements in inference batch sizes compared to the baseline, when optimizing
for the respective service level objectives.
