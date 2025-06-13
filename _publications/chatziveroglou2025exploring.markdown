---
layout: publication
title: 'Exploring LLM Reasoning Through Controlled Prompt Variations'
authors: Giannis Chatziveroglou, Richard Yun, Maura Kelleher
conference: "Arxiv"
year: 2025
bibkey: chatziveroglou2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02111"}
tags: ['Security', 'Prompting', 'Applications', 'Reinforcement Learning']
---
This study investigates the reasoning robustness of large language models
(LLMs) on mathematical problem-solving tasks under systematically introduced
input perturbations. Using the GSM8K dataset as a controlled testbed, we
evaluate how well state-of-the-art models maintain logical consistency and
correctness when confronted with four categories of prompt perturbations:
irrelevant context, pathological instructions, factually relevant but
non-essential context, and a combination of the latter two. Our experiments,
conducted on thirteen open-source and closed-source LLMs, reveal that
introducing irrelevant context within the model's context window significantly
degrades performance, suggesting that distinguishing essential from extraneous
details remains a pressing challenge. Surprisingly, performance regressions are
relatively insensitive to the complexity of the reasoning task, as measured by
the number of steps required, and are not strictly correlated with model size.
Moreover, we observe that certain perturbations inadvertently trigger
chain-of-thought-like reasoning behaviors, even without explicit prompting. Our
findings highlight critical vulnerabilities in current LLMs and underscore the
need for improved robustness against noisy, misleading, and contextually dense
inputs, paving the way for more resilient and reliable reasoning in real-world
applications.
