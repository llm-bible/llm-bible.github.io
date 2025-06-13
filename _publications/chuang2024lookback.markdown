---
layout: publication
title: 'Lookback Lens: Detecting And Mitigating Contextual Hallucinations In Large Language Models Using Only Attention Maps'
authors: Yung-sung Chuang, Linlu Qiu, Cheng-yu Hsieh, Ranjay Krishna, Yoon Kim, James Glass
conference: "Arxiv"
year: 2024
bibkey: chuang2024lookback
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.07071'}
tags: ['Attention Mechanism', 'Training Techniques', 'Applications', 'Model Architecture']
---
When asked to summarize articles or answer questions given a passage, large
language models (LLMs) can hallucinate details and respond with unsubstantiated
answers that are inaccurate with respect to the input context. This paper
describes a simple approach for detecting such contextual hallucinations. We
hypothesize that contextual hallucinations are related to the extent to which
an LLM attends to information in the provided context versus its own
generations. Based on this intuition, we propose a simple hallucination
detection model whose input features are given by the ratio of attention
weights on the context versus newly generated tokens (for each attention head).
We find that a linear classifier based on these lookback ratio features is as
effective as a richer detector that utilizes the entire hidden states of an LLM
or a text-based entailment model. The lookback ratio-based detector -- Lookback
Lens -- is found to transfer across tasks and even models, allowing a detector
that is trained on a 7B model to be applied (without retraining) to a larger
13B model. We further apply this detector to mitigate contextual
hallucinations, and find that a simple classifier-guided decoding approach is
able to reduce the amount of hallucination, for example by 9.6% in the XSum
summarization task.
