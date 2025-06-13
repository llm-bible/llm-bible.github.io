---
layout: publication
title: 'Routoo: Learning To Route To Large Language Models Effectively'
authors: Alireza Mohammadshahi, Arshad Rafiq Shaikh, Majid Yazdani
conference: "Arxiv"
year: 2024
bibkey: mohammadshahi2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13979"}
tags: ['Efficiency and Optimization', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
LLMs with superior response quality--particularly larger or closed-source
models--often come with higher inference costs, making their deployment
inefficient and costly. Meanwhile, developing foundational LLMs from scratch is
becoming increasingly resource-intensive and impractical for many applications.
To address the challenge of balancing quality and cost, we introduce Routoo, an
architecture designed to optimize the selection of LLMs for specific prompts
based on performance, cost, and efficiency. Routoo provides controllability
over the trade-off between inference cost and quality, enabling significant
reductions in inference costs for a given quality requirement. Routoo comprises
two key components: a performance predictor and cost-aware selector. The
performance predictor is a lightweight LLM that estimates the expected
performance of various underlying LLMs on a given prompt without executing
them. The cost-aware selector module then selects the most suitable model based
on these predictions and constraints such as cost and latency, significantly
reducing inference costs for the same quality. We evaluated Routoo using the
MMLU benchmark across 57 domains employing open-source models. Our results show
that Routoo matches the performance of the Mixtral 8x7b model while reducing
inference costs by one-third. Additionally, by allowing increased costs, Routoo
surpasses Mixtral's accuracy by over 5% at equivalent costs, achieving an
accuracy of 75.9%. When integrating GPT4 into our model pool, Routoo nearly
matches GPT4's performance at half the cost and exceeds it with a 25% cost
reduction. These outcomes highlight Routoo's potential to significantly reduce
inference costs without compromising quality, and even to establish new
state-of-the-art results by leveraging the collective capabilities of multiple
LLMs.
