---
layout: publication
title: 'Mitigating Entity-level Hallucination In Large Language Models'
authors: Weihang Su, Yichen Tang, Qingyao Ai, Changyue Wang, Zhijing Wu, Yiqun Liu
conference: "Arxiv"
year: 2024
bibkey: su2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09417"}
  - {name: "Code", url: "https://github.com/oneal2000/EntityHallucination"}
tags: ['Applications', 'Has Code']
---
The emergence of Large Language Models (LLMs) has revolutionized how users
access information, shifting from traditional search engines to direct
question-and-answer interactions with LLMs. However, the widespread adoption of
LLMs has revealed a significant challenge known as hallucination, wherein LLMs
generate coherent yet factually inaccurate responses. This hallucination
phenomenon has led to users' distrust in information retrieval systems based on
LLMs. To tackle this challenge, this paper proposes Dynamic Retrieval
Augmentation based on hallucination Detection (DRAD) as a novel method to
detect and mitigate hallucinations in LLMs. DRAD improves upon traditional
retrieval augmentation by dynamically adapting the retrieval process based on
real-time hallucination detection. It features two main components: Real-time
Hallucination Detection (RHD) for identifying potential hallucinations without
external models, and Self-correction based on External Knowledge (SEK) for
correcting these errors using external knowledge. Experiment results show that
DRAD demonstrates superior performance in both detecting and mitigating
hallucinations in LLMs. All of our code and data are open-sourced at
https://github.com/oneal2000/EntityHallucination.
