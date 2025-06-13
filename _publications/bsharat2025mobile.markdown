---
layout: publication
title: 'Mobile-mmlu: A Mobile Intelligence Language Understanding Benchmark'
authors: Sondos Mahmoud Bsharat, Mukul Ranjan, Aidar Myrzakhan, Jiacheng Liu, Bowei Guo, Shengkun Tang, Zhuang Liu, Yuanzhi Li, Zhiqiang Shen
conference: "Arxiv"
year: 2025
bibkey: bsharat2025mobile
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20786"}
  - {name: "Code", url: "https://github.com/VILA-Lab/Mobile-MMLU"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Ethics and Bias', 'RAG', 'Training Techniques', 'Has Code']
---
Rapid advancements in large language models (LLMs) have increased interest in
deploying them on mobile devices for on-device AI applications. Mobile users
interact differently with LLMs compared to desktop users, creating unique
expectations and data biases. Current benchmark datasets primarily target at
server and desktop environments, and there is a notable lack of extensive
datasets specifically designed for mobile contexts. Additionally, mobile
devices face strict limitations in storage and computing resources,
constraining model size and capabilities, thus requiring optimized efficiency
and prioritized knowledge. To address these challenges, we introduce
Mobile-MMLU, a large-scale benchmark dataset tailored for mobile intelligence.
It consists of 16,186 questions across 80 mobile-related fields, designed to
evaluate LLM performance in realistic mobile scenarios. A challenging subset,
Mobile-MMLU-Pro, provides advanced evaluation similar in size to MMLU-Pro but
significantly more difficult than our standard full set. Both benchmarks use
multiple-choice, order-invariant questions focused on practical mobile
interactions, such as recipe suggestions, travel planning, and essential daily
tasks. The dataset emphasizes critical mobile-specific metrics like inference
latency, energy consumption, memory usage, and response quality, offering
comprehensive insights into model performance under mobile constraints.
Moreover, it prioritizes privacy and adaptability, assessing models' ability to
perform on-device processing, maintain user privacy, and adapt to personalized
usage patterns. Mobile-MMLU family offers a standardized framework for
developing and comparing mobile-optimized LLMs, enabling advancements in
productivity and decision-making within mobile computing environments. Our code
and data are available at: https://github.com/VILA-Lab/Mobile-MMLU.
