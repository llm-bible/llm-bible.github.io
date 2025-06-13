---
layout: publication
title: 'Semantics Preserving Emoji Recommendation With Large Language Models'
authors: Zhongyi Qiu, Kangyi Qiu, Hanjia Lyu, Wei Xiong, Jiebo Luo
conference: "Arxiv"
year: 2024
bibkey: qiu2024semantics
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10760"}
tags: ['Tools', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Emojis have become an integral part of digital communication, enriching text
by conveying emotions, tone, and intent. Existing emoji recommendation methods
are primarily evaluated based on their ability to match the exact emoji a user
chooses in the original text. However, they ignore the essence of users'
behavior on social media in that each text can correspond to multiple
reasonable emojis. To better assess a model's ability to align with such
real-world emoji usage, we propose a new semantics preserving evaluation
framework for emoji recommendation, which measures a model's ability to
recommend emojis that maintain the semantic consistency with the user's text.
To evaluate how well a model preserves semantics, we assess whether the
predicted affective state, demographic profile, and attitudinal stance of the
user remain unchanged. If these attributes are preserved, we consider the
recommended emojis to have maintained the original semantics. The advanced
abilities of Large Language Models (LLMs) in understanding and generating
nuanced, contextually relevant output make them well-suited for handling the
complexities of semantics preserving emoji recommendation. To this end, we
construct a comprehensive benchmark to systematically assess the performance of
six proprietary and open-source LLMs using different prompting techniques on
our task. Our experiments demonstrate that GPT-4o outperforms other LLMs,
achieving a semantics preservation score of 79.23%. Additionally, we conduct
case studies to analyze model biases in downstream classification tasks and
evaluate the diversity of the recommended emojis.
