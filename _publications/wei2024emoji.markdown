---
layout: publication
title: 'Emoji Attack: Enhancing Jailbreak Attacks Against Judge LLM Detection'
authors: Zhipeng Wei, Yuqi Liu, N. Benjamin Erichson
conference: "Arxiv"
year: 2024
bibkey: wei2024emoji
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.01077'}
tags: ['In-Context Learning', 'RAG', 'Security', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Tokenization']
---
Jailbreaking techniques trick Large Language Models (LLMs) into producing
restricted outputs, posing a serious threat. One line of defense is to use
another LLM as a Judge to evaluate the harmfulness of generated text. However,
we reveal that these Judge LLMs are vulnerable to token segmentation bias, an
issue that arises when delimiters alter the tokenization process, splitting
words into smaller sub-tokens. This disrupts the embeddings of the entire
sequence, reducing detection accuracy and allowing harmful content to be
misclassified as safe. In this paper, we introduce Emoji Attack, a novel
strategy that amplifies existing jailbreak prompts by exploiting token
segmentation bias. Our method leverages in-context learning to systematically
insert emojis into text before it is evaluated by a Judge LLM, inducing
embedding distortions that significantly lower the likelihood of detecting
unsafe content. Unlike traditional delimiters, emojis also introduce semantic
ambiguity, making them particularly effective in this attack. Through
experiments on state-of-the-art Judge LLMs, we demonstrate that Emoji Attack
substantially reduces the "unsafe" prediction rate, bypassing existing
safeguards.
