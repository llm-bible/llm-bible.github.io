---
layout: publication
title: 'Alleviating The Fear Of Losing Alignment In LLM Fine-tuning'
authors: Kang Yang, Guanhong Tao, Xun Chen, Jun Xu
conference: "Arxiv"
year: 2025
bibkey: yang2025alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09757"}
  - {name: "Code", url: "https://github.com/kangyangWHU/LLMAlignment"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated revolutionary capabilities in
understanding complex contexts and performing a wide range of tasks. However,
LLMs can also answer questions that are unethical or harmful, raising concerns
about their applications. To regulate LLMs' responses to such questions, a
training strategy called \textit\{alignment\} can help. Yet, alignment can be
unexpectedly compromised when fine-tuning an LLM for downstream tasks. This
paper focuses on recovering the alignment lost during fine-tuning.
  We observe that there are two distinct directions inherent in an aligned LLM:
the \textit\{aligned direction\} and the \textit\{harmful direction\}. An LLM is
inclined to answer questions in the aligned direction while refusing queries in
the harmful direction. Therefore, we propose to recover the harmful direction
of the fine-tuned model that has been compromised. Specifically, we restore a
small subset of the fine-tuned model's weight parameters from the original
aligned model using gradient descent. We also introduce a rollback mechanism to
avoid aggressive recovery and maintain downstream task performance. Our
evaluation on 125 fine-tuned LLMs demonstrates that our method can reduce their
harmful rate (percentage of answering harmful questions) from 33.25% to
1.74%, without sacrificing task performance much. In contrast, the existing
methods either only reduce the harmful rate to a limited extent or
significantly impact the normal functionality. Our code is available at
https://github.com/kangyangWHU/LLMAlignment
