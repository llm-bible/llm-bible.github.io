---
layout: publication
title: Learning Fine45;grained Grounded Citations For Attributed Large Language Models
authors: Huang Lei, Feng Xiaocheng, Ma Weitao, Gu Yuxuan, Zhong Weihong, Feng Xiachong, Yu Weijiang, Peng Weihua, Tang Duyu, Tu Dandan, Qin Bing
conference: "Arxiv"
year: 2024
bibkey: huang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04568"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Despite the impressive performance on information45;seeking tasks large language models (LLMs) still struggle with hallucinations. Attributed LLMs which augment generated text with in45;line citations have shown potential in mitigating hallucinations and improving verifiability. However current approaches suffer from suboptimal citation quality due to their reliance on in45;context learning. Furthermore the practice of citing only coarse document identifiers makes it challenging for users to perform fine45;grained verification. In this work we introduce FRONT a training framework designed to teach LLMs to generate Fine45;Grained Grounded Citations. By grounding model outputs in fine45;grained supporting quotes these quotes guide the generation of grounded and consistent responses not only improving citation quality but also facilitating fine45;grained verification. Experiments on the ALCE benchmark demonstrate the efficacy of FRONT in generating superior grounded responses and highly supportive citations. With LLaMA45;245;7B the framework significantly outperforms all the baselines achieving an average of 14.2137; improvement in citation quality across all datasets even surpassing ChatGPT.
