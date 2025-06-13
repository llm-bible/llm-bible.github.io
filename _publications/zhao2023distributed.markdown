---
layout: publication
title: 'Lingualinked: A Distributed Large Language Model Inference System For Mobile Devices'
authors: Junchen Zhao, Yurun Song, Simeng Liu, Ian G. Harris, Sangeetha Abdu Jyothi
conference: "Arxiv"
year: 2023
bibkey: zhao2023distributed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00388"}
tags: ['Efficiency and Optimization']
---
Deploying Large Language Models (LLMs) locally on mobile devices presents a
significant challenge due to their extensive memory requirements. In this
paper, we introduce LinguaLinked, a system for decentralized, distributed LLM
inference on mobile devices. LinguaLinked enables collaborative execution of
the inference task across multiple trusted devices. LinguaLinked ensures data
privacy by processing information locally. LinguaLinked uses three key
strategies. First, an optimized model assignment technique segments LLMs and
uses linear optimization to align segments with each device's capabilities.
Second, an optimized data transmission mechanism ensures efficient and
structured data flow between model segments while also maintaining the
integrity of the original model structure. Finally, LinguaLinked incorporates a
runtime load balancer that actively monitors and redistributes tasks among
mobile devices to prevent bottlenecks, enhancing the system's overall
efficiency and responsiveness. We demonstrate that LinguaLinked facilitates
efficient LLM inference while maintaining consistent throughput and minimal
latency through extensive testing across various mobile devices, from high-end
to low-end Android devices. In our evaluations, compared to the baseline,
LinguaLinked achieves an inference performance acceleration of \\(1.11\times\\) to
\\(1.61\times\\) in single-threaded settings, \\(1.73\times\\) to \\(2.65\times\\) with
multi-threading. Additionally, runtime load balancing yields an overall
inference acceleration of \\(1.29\times\\) to \\(1.32\times\\).
