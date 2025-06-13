---
layout: publication
title: 'Eliciting Personality Traits In Large Language Models'
authors: Airlie Hilliard, Cristian Munoz, Zekun Wu, Adriano Soares Koshiyama
conference: "Arxiv"
year: 2024
bibkey: hilliard2024eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08341"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Interpretability', 'Prompting']
---
Large Language Models (LLMs) are increasingly being utilized by both
candidates and employers in the recruitment context. However, with this comes
numerous ethical concerns, particularly related to the lack of transparency in
these "black-box" models. Although previous studies have sought to increase the
transparency of these models by investigating the personality traits of LLMs,
many of the previous studies have provided them with personality assessments to
complete. On the other hand, this study seeks to obtain a better understanding
of such models by examining their output variations based on different input
prompts. Specifically, we use a novel elicitation approach using prompts
derived from common interview questions, as well as prompts designed to elicit
particular Big Five personality traits to examine whether the models were
susceptible to trait-activation like humans are, to measure their personality
based on the language used in their outputs. To do so, we repeatedly prompted
multiple LMs with different parameter sizes, including Llama-2, Falcon,
Mistral, Bloom, GPT, OPT, and XLNet (base and fine tuned versions) and examined
their personality using classifiers trained on the myPersonality dataset. Our
results reveal that, generally, all LLMs demonstrate high openness and low
extraversion. However, whereas LMs with fewer parameters exhibit similar
behaviour in personality traits, newer and LMs with more parameters exhibit a
broader range of personality traits, with increased agreeableness, emotional
stability, and openness. Furthermore, a greater number of parameters is
positively associated with openness and conscientiousness. Moreover, fine-tuned
models exhibit minor modulations in their personality traits, contingent on the
dataset. Implications and directions for future research are discussed.
