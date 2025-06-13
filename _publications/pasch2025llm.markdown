---
layout: publication
title: 'LLM Content Moderation And User Satisfaction: Evidence From Response Refusals In Chatbot Arena'
authors: Stefan Pasch
conference: "Arxiv"
year: 2025
bibkey: pasch2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03266"}
tags: ['Responsible AI', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'BERT', 'Prompting']
---
LLM safety and ethical alignment are widely discussed, but the impact of content moderation on user satisfaction remains underexplored. In particular, little is known about how users respond when models refuse to answer a prompt-one of the primary mechanisms used to enforce ethical boundaries in LLMs. We address this gap by analyzing nearly 50,000 model comparisons from Chatbot Arena, a platform where users indicate their preferred LLM response in pairwise matchups, providing a large-scale setting for studying real-world user preferences. Using a novel RoBERTa-based refusal classifier fine-tuned on a hand-labeled dataset, we distinguish between refusals due to ethical concerns and technical limitations. Our results reveal a substantial refusal penalty: ethical refusals yield significantly lower win rates than both technical refusals and standard responses, indicating that users are especially dissatisfied when models decline a task for ethical reasons. However, this penalty is not uniform. Refusals receive more favorable evaluations when the underlying prompt is highly sensitive (e.g., involving illegal content), and when the refusal is phrased in a detailed and contextually aligned manner. These findings underscore a core tension in LLM design: safety-aligned behaviors may conflict with user expectations, calling for more adaptive moderation strategies that account for context and presentation.
