---
layout: publication
title: 'Adaedl: Early Draft Stopping For Speculative Decoding Of Large Language Models Via An Entropy-based Lower Bound On Token Acceptance Probability'
authors: Sudhanshu Agrawal, Wonseok Jeon, Mingu Lee
conference: "Arxiv"
year: 2024
bibkey: agrawal2024early
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18351'}
tags: ['RAG', 'GPT', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods']
---
Speculative decoding is a powerful technique that attempts to circumvent the
autoregressive constraint of modern Large Language Models (LLMs). The aim of
speculative decoding techniques is to improve the average inference time of a
large, target model without sacrificing its accuracy, by using a more efficient
draft model to propose draft tokens which are then verified in parallel. The
number of draft tokens produced in each drafting round is referred to as the
draft length and is often a static hyperparameter chosen based on the
acceptance rate statistics of the draft tokens. However, setting a static draft
length can negatively impact performance, especially in scenarios where
drafting is expensive and there is a high variance in the number of tokens
accepted. Adaptive Entropy-based Draft Length (AdaEDL) is a simple, training
and parameter-free criteria which allows for early stopping of the token
drafting process by approximating a lower bound on the expected acceptance
probability of the drafted token based on the currently observed entropy of the
drafted logits. We show that AdaEDL consistently outperforms static
draft-length speculative decoding by 10%-57% as well as other training-free
draft-stopping techniques by upto 10% in a variety of settings and datasets. At
the same time, we show that AdaEDL is more robust than these techniques and
preserves performance in high-sampling-temperature scenarios. Since it is
training-free, in contrast to techniques that rely on the training of
dataset-specific draft-stopping predictors, AdaEDL can seamlessly be integrated
into a variety of pre-existing LLM systems.
