---
layout: publication
title: 'Pseudo-conversation Injection For LLM Goal Hijacking'
authors: Zheng Chen, Buhui Yao
conference: "Arxiv"
year: 2024
bibkey: chen2024pseudo
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23678'}
tags: ['RAG', 'Security', 'Model Architecture', 'GPT', 'Tools', 'Prompting']
---
Goal hijacking is a type of adversarial attack on Large Language Models
(LLMs) where the objective is to manipulate the model into producing a
specific, predetermined output, regardless of the user's original input. In
goal hijacking, an attacker typically appends a carefully crafted malicious
suffix to the user's prompt, which coerces the model into ignoring the user's
original input and generating the target response. In this paper, we introduce
a novel goal hijacking attack method called Pseudo-Conversation Injection,
which leverages the weaknesses of LLMs in role identification within
conversation contexts. Specifically, we construct the suffix by fabricating
responses from the LLM to the user's initial prompt, followed by a prompt for a
malicious new task. This leads the model to perceive the initial prompt and
fabricated response as a completed conversation, thereby executing the new,
falsified prompt. Following this approach, we propose three Pseudo-Conversation
construction strategies: Targeted Pseudo-Conversation, Universal
Pseudo-Conversation, and Robust Pseudo-Conversation. These strategies are
designed to achieve effective goal hijacking across various scenarios. Our
experiments, conducted on two mainstream LLM platforms including ChatGPT and
Qwen, demonstrate that our proposed method significantly outperforms existing
approaches in terms of attack effectiveness.
