---
layout: publication
title: 'Beyond English-centric Llms: What Language Do Multilingual Language Models Think In?'
authors: Chengzhi Zhong, Fei Cheng, Qianying Liu, Junfeng Jiang, Zhen Wan, Chenhui Chu, Yugo Murawaki, Sadao Kurohashi
conference: "Arxiv"
year: 2024
bibkey: zhong2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10811"}
tags: ['Training Techniques', 'Pre-Training']
---
In this study, we investigate whether non-English-centric LLMs, despite their
strong performance, `think' in their respective dominant language: more
precisely, `think' refers to how the representations of intermediate layers,
when un-embedded into the vocabulary space, exhibit higher probabilities for
certain dominant languages during generation. We term such languages as
internal \\(\textbf\{latent languages\}\\).
  We examine the latent language of three typical categories of models for
Japanese processing: Llama2, an English-centric model; Swallow, an
English-centric model with continued pre-training in Japanese; and LLM-jp, a
model pre-trained on balanced English and Japanese corpora. Our empirical
findings reveal that, unlike Llama2 which relies exclusively on English as the
internal latent language, Japanese-specific Swallow and LLM-jp employ both
Japanese and English, exhibiting dual internal latent languages. For any given
target language, the model preferentially activates the latent language most
closely related to it. In addition, we explore how intermediate layers respond
to questions involving cultural conflicts between latent internal and target
output languages. We further explore how the language identity shifts across
layers while keeping consistent semantic meaning reflected in the intermediate
layer representations.
  This study deepens the understanding of non-English-centric large language
models, highlighting the intricate dynamics of language representation within
their intermediate layers.
