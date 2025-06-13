---
layout: publication
title: 'Ce-collm: Efficient And Adaptive Large Language Models Through Cloud-edge Collaboration'
authors: Hongpeng Jin, Yanzhao Wu
conference: "Arxiv"
year: 2024
bibkey: jin2024ce
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02829'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Tools', 'Quantization']
---
Large Language Models (LLMs) have achieved remarkable success in serving
end-users with human-like intelligence. However, LLMs demand high computational
resources, making it challenging to deploy them to satisfy various performance
objectives, such as meeting the resource constraints on edge devices close to
end-users or achieving high accuracy with ample resources. In this paper, we
introduce CE-CoLLM, a novel cloud-edge collaboration framework that supports
efficient and adaptive LLM inference for end-users at the edge with two modes,
(1) low-latency edge standalone inference and (2) highly accurate cloud-edge
collaborative inference. First, we show that the inherent high communication
costs for transmitting LLM contextual information between the edge and cloud
dominate the overall latency, making it inefficient and costly to deploy LLMs
using cloud-edge collaboration. Second, we propose several critical techniques
to address this challenge, including early-exit mechanism, cloud context
manager, and quantization in cloud-edge collaboration to enable not only
low-latency standalone edge inference but also efficient and adaptive
cloud-edge collaborative inference for LLMs. Third, we perform comprehensive
experimental analysis, which demonstrates that CE-CoLLM significantly reduces
inference time by up to 13.81% and cloud computation costs by up to 84.55%
compared to the popular cloud-based LLM deployment, while maintaining
comparable model accuracy. The proposed approach effectively shifts the
computational load to the edge, reduces the communication overhead, scales
efficiently with multiple edge clients, and provides reliable LLM deployment
using cloud-edge collaboration.
