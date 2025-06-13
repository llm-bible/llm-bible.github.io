---
layout: publication
title: 'Deltazip: Efficient Serving Of Multiple Full-model-tuned Llms'
authors: Xiaozhe Yao, Qinghao Hu, Ana Klimovic
conference: "Arxiv"
year: 2023
bibkey: yao2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05215"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) greatly improves model quality for
downstream tasks. However, serving many fine-tuned LLMs concurrently is
challenging due to the sporadic, bursty, and varying request patterns of
different LLMs. To bridge this gap, we present DeltaZip, an LLM serving system
that efficiently serves multiple full-parameter fine-tuned models concurrently
by aggressively compressing model deltas by up to 10x while maintaining high
model quality. The key insight behind this design is that fine-tuning results
in small-magnitude changes to the pre-trained model. By co-designing the
serving system with the compression algorithm, DeltaZip achieves 2x to 12x
improvement in throughput compared to the state-of-the-art systems.
