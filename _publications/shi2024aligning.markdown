---
layout: publication
title: 'Wildfeedback: Aligning Llms With In-situ User Interactions And Feedback'
authors: Taiwei Shi, Zhuoer Wang, Longqi Yang, Ying-chun Lin, Zexue He, Mengting Wan, Pei Zhou, Sujay Jauhar, Sihao Chen, Shan Xia, Hongfei Zhang, Jieyu Zhao, Xiaofeng Xu, Xia Song, Jennifer Neville
conference: "Arxiv"
year: 2024
bibkey: shi2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15549"}
tags: ['RAG', 'Tools', 'Ethics and Bias', 'Reinforcement Learning']
---
As large language models (LLMs) continue to advance, aligning these models
with human preferences has emerged as a critical challenge. Traditional
alignment methods, relying on human or LLM annotated datasets, are limited by
their resource-intensive nature, inherent subjectivity, misalignment with
real-world user preferences, and the risk of feedback loops that amplify model
biases. To overcome these limitations, we introduce WildFeedback, a novel
framework that leverages in-situ user feedback during conversations with LLMs
to create preference datasets automatically. Given a corpus of multi-turn
user-LLM conversation, WildFeedback identifies and classifies user feedback to
LLM responses between conversation turns. The user feedback is then used to
create examples of preferred and dispreferred responses according to users'
preference. Our experiments demonstrate that LLMs fine-tuned on WildFeedback
dataset exhibit significantly improved alignment with user preferences, as
evidenced by both traditional benchmarks and our proposed checklist-guided
evaluation. By incorporating in-situ feedback from actual users, WildFeedback
addresses the scalability, subjectivity, and bias challenges that plague
existing approaches, marking a significant step toward developing LLMs that are
more responsive to the diverse and evolving needs of their users.
