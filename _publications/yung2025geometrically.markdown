---
layout: publication
title: 'CURVALID: Geometrically-guided Adversarial Prompt Detection'
authors: Canaan Yung, Hanxun Huang, Sarah Monazam Erfani, Christopher Leckie
conference: "Arxiv"
year: 2025
bibkey: yung2025geometrically
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03502'}
  - {name: "Code", url: 'https://github.com/Cancanxxx/CurvaLID'}
tags: ['Has Code', 'ACL', 'RAG', 'Security', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'TACL', 'Pretraining Methods']
---
Adversarial prompts capable of jailbreaking large language models (LLMs) and
inducing undesirable behaviours pose a significant obstacle to their safe
deployment. Current mitigation strategies rely on activating built-in defence
mechanisms or fine-tuning the LLMs, but the fundamental distinctions between
adversarial and benign prompts are yet to be understood. In this work, we
introduce CurvaLID, a novel defense framework that efficiently detects
adversarial prompts by leveraging their geometric properties. It is agnostic to
the type of LLM, offering a unified detection framework across diverse
adversarial prompts and LLM architectures. CurvaLID builds on the geometric
analysis of text prompts to uncover their underlying differences. We
theoretically extend the concept of curvature via the Whewell equation into an
\\(n\\)-dimensional word embedding space, enabling us to quantify local geometric
properties, including semantic shifts and curvature in the underlying
manifolds. Additionally, we employ Local Intrinsic Dimensionality (LID) to
capture geometric features of text prompts within adversarial subspaces. Our
findings reveal that adversarial prompts differ fundamentally from benign
prompts in terms of their geometric characteristics. Our results demonstrate
that CurvaLID delivers superior detection and rejection of adversarial queries,
paving the way for safer LLM deployment. The source code can be found at
https://github.com/Cancanxxx/CurvaLID
