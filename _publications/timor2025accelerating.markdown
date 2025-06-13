---
layout: publication
title: 'Accelerating LLM Inference With Lossless Speculative Decoding Algorithms For Heterogeneous Vocabularies'
authors: Nadav Timor, Jonathan Mamou, Daniel Korat, Moshe Berchansky, Oren Pereg, Gaurav Jain, Roy Schwartz, Moshe Wasserblat, David Harel
conference: "Arxiv"
year: 2025
bibkey: timor2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05202"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'GPT', 'Pretraining Methods', 'Applications']
---
Accelerating the inference of large language models (LLMs) is a critical
challenge in generative AI. Speculative decoding (SD) methods offer substantial
efficiency gains by generating multiple tokens using a single target forward
pass. However, existing SD approaches require the drafter and target models to
share the same vocabulary, thus limiting the pool of possible drafters, often
necessitating the training of a drafter from scratch. We present three new SD
methods that remove this shared-vocabulary constraint. All three methods
preserve the target distribution (i.e., they are lossless) and work with
off-the-shelf models without requiring additional training or modifications.
Empirically, on summarization, programming, and long-context tasks, our
algorithms achieve significant speedups over standard autoregressive decoding.
By enabling any off-the-shelf model to serve as drafter and requiring no
retraining, this work substantially broadens the applicability of the SD
framework in practice.
