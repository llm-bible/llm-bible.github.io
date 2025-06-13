---
layout: publication
title: 'Andes: Defining And Enhancing Quality-of-experience In Llm-based Text Streaming Services'
authors: Jiachen Liu, Jae-won Chung, Zhiyu Wu, Fan Lai, Myungjin Lee, Mosharaf Chowdhury
conference: "Arxiv"
year: 2024
bibkey: liu2024defining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16283"}
tags: ['Prompting', 'RAG', 'Efficiency and Optimization']
---
Large language models (LLMs) are now at the core of conversational AI
services such as real-time translation and chatbots, which provide live user
interaction by incrementally streaming text to the user. However, existing LLM
serving systems fail to provide good user experience because their optimization
metrics are not always aligned with user experience.
  In this paper, we first introduce and define the notion of
Quality-of-Experience (QoE) for text streaming services by considering each
user's end-to-end interaction timeline. Based on this, we propose Andes, a
QoE-aware LLM serving system that enhances user experience by ensuring that
users receive the first token promptly and subsequent tokens at a smooth,
digestible pace, even during surge periods. This is enabled by Andes's
preemptive request scheduler that dynamically prioritizes requests at the token
granularity based on each request's expected QoE gain and GPU resource usage.
Our evaluations demonstrate that, compared to state-of-the-art LLM serving
systems, Andes improves the average QoE by up to \\(4.7\times\\) given the same GPU
resource, or saves up to 61% GPU resources while maintaining the same high QoE.
