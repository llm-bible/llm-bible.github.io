---
layout: publication
title: 'Streaming, Fast And Slow: Cognitive Load-aware Streaming For Efficient LLM Serving'
authors: Chang Xiao, Brenda Yang
conference: "Arxiv"
year: 2025
bibkey: xiao2025fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17999"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Generative conversational interfaces powered by large language models (LLMs)
typically stream output token-by-token at a rate determined by computational
budget, often neglecting actual human reading speeds and the cognitive load
associated with the content. This mismatch frequently leads to inefficient use
of computational resources. For example, in cloud-based services, streaming
content faster than users can read appears unnecessary, resulting in wasted
computational resources and potential delays for other users, particularly
during peak usage periods. To address this issue, we propose an adaptive
streaming method that dynamically adjusts the pacing of LLM streaming output in
real-time based on inferred cognitive load. Our approach estimates the
cognitive load associated with streaming content and strategically slows down
the stream during complex or information-rich segments, thereby freeing
computational resources for other users. Our statistical analysis of
computational savings, combined with crowdsourced user studies, provides
insights into the trade-offs between service efficiency and user satisfaction,
demonstrating that our method can significantly reduce computational
consumption up to 16.8%. This context-aware computational resource management
strategy presents a practical framework for enhancing system efficiency in
cloud-based conversational AI interfaces without compromising user experience.
