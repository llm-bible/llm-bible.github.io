---
layout: publication
title: 'Structured Packing In LLM Training Improves Long Context Utilization'
authors: Konrad Staniszewski, Szymon Tworkowski, Sebastian Jaszczur, Yu Zhao, Henryk Michalewski, Łukasz Kuciński, Piotr Miłoś
conference: "Arxiv"
year: 2023
bibkey: staniszewski2023structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17296"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Recent advancements in long-context large language models have attracted
significant attention, yet their practical applications often suffer from
suboptimal context utilization. This study investigates structuring training
data to enhance semantic interdependence, demonstrating that this approach
effectively improves context utilization. To this end, we introduce the
Structured Packing for Long Context (SPLiCe) method, which utilizes retrieval
to collate mutually relevant documents into long and coherent training
examples. We validate SPLiCe empirically across models of varying sizes -- 3B,
7B, and 13B -- achieving improved performance in long-context tasks, such as
Qasper and HotpotQA. Remarkably, even brief fine-tuning with SPLiCe is
sufficient to realize these benefits. Additionally, SPLiCe effectively
mitigates the lost-in-middle phenomenon often observed in large models. Our
comprehensive analysis of SPLiCe explores its design choices and reveals
intriguing transfer effects; for instance, training on programming code
enhances performance on natural language tasks.
