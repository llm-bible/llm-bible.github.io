---
layout: publication
title: 'Personalized Language Modeling From Personalized Human Feedback'
authors: Xinyu Li, Ruiyang Zhou, Zachary C. Lipton, Liu Leqi
conference: "Arxiv"
year: 2024
bibkey: li2024personalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.05133'}
  - {name: "Code", url: 'https://github.com/HumainLab/Personalized_RLHF'}
tags: ['Agentic', 'Has Code', 'Language Modeling', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Personalized large language models (LLMs) are designed to tailor responses to
individual user preferences. While Reinforcement Learning from Human Feedback
(RLHF) is a commonly used framework for aligning LLMs with human preferences,
vanilla RLHF assumes that all human preferences share the same distribution,
preventing fine-tuned LLMs from generating personalized content when user
preferences are diverse. In this work, we propose Personalized-RLHF (P-RLHF),
an efficient framework that utilizes a lightweight user model to capture
individual user preferences and jointly learns the user model and the
personalized LLM from human feedback. P-RLHF exhibits the following three
characteristics: (1) It enables an LLM to generate personalized content and
scale efficiently with growing number of users. (2) It handles both explicit
user preferences described as textual input and implicit user preferences
encoded in the feedback data. (3) It eliminates the need for users to fully
articulate their preferences, which are normally needed for prompting LLMs to
generate personalized content yet are often impractical to obtain in real-world
scenarios. Our experimental results show that personalized LLMs trained using
P-RLHF generate responses that are more closely aligned with individual user
preferences, outperforming vanilla, non-personalized RLHF and prompting-based
personalization approaches across different tasks. We opensource our code at
https://github.com/HumainLab/Personalized_RLHF.
