---
layout: publication
title: 'Detecting Hallucinations In Large Language Model Generation: A Token Probability Approach'
authors: Quevedo Ernesto, Yero Jorge, Koerner Rachel, Rivas Pablo, Cerny Tomas
conference: "Arxiv"
year: 2024
bibkey: quevedo2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19648"}
  - {name: "Code", url: "https://github.com/Baylor-AI/HalluDetect"}
tags: ['Applications', 'Has Code', 'Uncategorized']
---
Concerns regarding the propensity of Large Language Models (LLMs) to produce inaccurate outputs, also known as hallucinations, have escalated. Detecting them is vital for ensuring the reliability of applications relying on LLM-generated content. Current methods often demand substantial resources and rely on extensive LLMs or employ supervised learning with multidimensional features or intricate linguistic and semantic analyses difficult to reproduce and largely depend on using the same LLM that hallucinated. This paper introduces a supervised learning approach employing two simple classifiers utilizing only four numerical features derived from tokens and vocabulary probabilities obtained from other LLM evaluators, which are not necessarily the same. The method yields promising results, surpassing state-of-the-art outcomes in multiple tasks across three different benchmarks. Additionally, we provide a comprehensive examination of the strengths and weaknesses of our approach, highlighting the significance of the features utilized and the LLM employed as an evaluator. We have released our code publicly at https://github.com/Baylor-AI/HalluDetect.
