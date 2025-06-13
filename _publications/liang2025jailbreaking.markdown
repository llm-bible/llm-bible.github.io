---
layout: publication
title: 'Jailbreaking Llms'' Safeguard With Universal Magic Words For Text Embedding Models'
authors: Haoyu Liang, Youran Sun, Yunfeng Cai, Jun Zhu, Bo Zhang
conference: "Arxiv"
year: 2025
bibkey: liang2025jailbreaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18280'}
tags: ['Attention Mechanism', 'Security', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
The security issue of large language models (LLMs) has gained wide attention recently, with various defense mechanisms developed to prevent harmful output, among which safeguards based on text embedding models serve as a fundamental defense. Through testing, we discover that the output distribution of text embedding models is severely biased with a large mean. Inspired by this observation, we propose novel, efficient methods to search for **universal magic words** that attack text embedding models. Universal magic words as suffixes can shift the embedding of any text towards the bias direction, thus manipulating the similarity of any text pair and misleading safeguards. Attackers can jailbreak the safeguards by appending magic words to user prompts and requiring LLMs to end answers with magic words. Experiments show that magic word attacks significantly degrade safeguard performance on JailbreakBench, cause real-world chatbots to produce harmful outputs in full-pipeline attacks, and generalize across input/output texts, models, and languages. To eradicate this security risk, we also propose defense methods against such attacks, which can correct the bias of text embeddings and improve downstream performance in a train-free manner.
