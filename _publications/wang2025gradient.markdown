---
layout: publication
title: 'Gradient-guided Attention Map Editing: Towards Efficient Contextual Hallucination Mitigation'
authors: Yu Wang, Jiaxin Zhang, Xiang Gao, Wendi Cui, Peng Li, Kamalika Das
conference: "Arxiv"
year: 2025
bibkey: wang2025gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08963"}
tags: ['Efficiency and Optimization', 'Attention Mechanism', 'Applications', 'Model Architecture']
---
In tasks like summarization and open-book question answering (QA), Large
Language Models (LLMs) often encounter "contextual hallucination", where they
produce irrelevant or incorrect responses despite having access to accurate
source information. This typically occurs because these models tend to
prioritize self-generated content over the input context, causing them to
disregard pertinent details. To address this challenge, we introduce a novel
method called "Guided Attention Map Editing" (GAME), which dynamically adjusts
attention maps to improve contextual relevance. During inference, GAME employs
a trained classifier to identify attention maps prone to inducing
hallucinations and executes targeted interventions. These interventions, guided
by gradient-informed "edit directions'', strategically redistribute attention
weights across various heads to effectively reduce hallucination. Comprehensive
evaluations on challenging summarization and open-book QA tasks show that GAME
consistently reduces hallucinations across a variety of open-source models.
Specifically, GAME reduces hallucinations by 10% in the XSum summarization task
while achieving a 7X speed-up in computational efficiency compared to the
state-of-the-art baselines.
