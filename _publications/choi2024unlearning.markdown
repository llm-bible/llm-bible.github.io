---
layout: publication
title: 'SNAP: Unlearning Selective Knowledge In Large Language Models With Negative Instructions'
authors: Choi Minseok, Rim Daniel, Lee Dohyun, Choo Jaegul
conference: "Arxiv"
year: 2024
bibkey: choi2024unlearning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12329"}
tags: ['GPT', 'Model Architecture', 'Tools', 'Training Techniques']
---
Instruction-following large language models (LLMs), such as ChatGPT, have
become increasingly popular with the general audience, many of whom are
incorporating them into their daily routines. However, these LLMs inadvertently
disclose personal or copyrighted information, which calls for a machine
unlearning method to remove selective knowledge. Previous attempts sought to
forget the link between the target information and its associated entities, but
it rather led to generating undesirable responses about the target,
compromising the end-user experience. In this work, we propose SNAP, an
innovative framework designed to selectively unlearn information by 1) training
an LLM with negative instructions to generate obliterated responses, 2)
augmenting hard positives to retain the original LLM performance, and 3)
applying the novel Wasserstein regularization to ensure adequate deviation from
the initial weights of the LLM. We evaluate our framework on various NLP
benchmarks and demonstrate that our approach retains the original LLM
capabilities, while successfully unlearning the specified information.
