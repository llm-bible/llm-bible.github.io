---
layout: publication
title: Iclguard Controlling In-context Learning Behavior For Applicability Authorization
authors: Si Wai Man, Backes Michael, Zhang Yang
conference: "Arxiv"
year: 2024
bibkey: si2024iclguard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06955"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In-context learning (ICL) is a recent advancement in the capabilities of large language models (LLMs). This feature allows users to perform a new task without updating the model. Concretely users can address tasks during the inference time by conditioning on a few input-label pair demonstrations along with the test input. It is different than the conventional fine-tuning paradigm and offers more flexibility. However this capability also introduces potential issues. For example users may use the model on any data without restriction such as performing tasks with improper or sensitive content which might violate the model policy or conflict with the model owners interests. As a model owner it is crucial to establish a mechanism to control the models behavior under ICL depending on the model owners requirements for various content. To this end we introduce the concept of applicability authorization tailored for LLMs particularly for ICL behavior and propose a simple approach ICLGuard. It is a fine-tuning framework designed to allow the model owner to regulate ICL behavior on different data. ICLGuard preserves the original LLM and fine-tunes only a minimal set of additional trainable parameters to guard the LLM. Empirical results show that the guarded LLM can deactivate its ICL ability on target data without affecting its ICL ability on other data and its general functionality across all data.
