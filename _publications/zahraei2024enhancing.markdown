---
layout: publication
title: 'WSC+: Enhancing The Winograd Schema Challenge Using Tree-of-experts'
authors: Pardis Sadat Zahraei, Ali Emami
conference: "Arxiv"
year: 2024
bibkey: zahraei2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.17703'}
tags: ['Model Architecture', 'Tools', 'GPT', 'Prompting', 'Ethics and Bias']
---
The Winograd Schema Challenge (WSC) serves as a prominent benchmark for
evaluating machine understanding. While Large Language Models (LLMs) excel at
answering WSC questions, their ability to generate such questions remains less
explored. In this work, we propose Tree-of-Experts (ToE), a novel prompting
method which enhances the generation of WSC instances (50% valid cases vs. 10%
in recent methods). Using this approach, we introduce WSC+, a novel dataset
comprising 3,026 LLM-generated sentences. Notably, we extend the WSC framework
by incorporating new 'ambiguous' and 'offensive' categories, providing a deeper
insight into model overconfidence and bias. Our analysis reveals nuances in
generation-evaluation consistency, suggesting that LLMs may not always
outperform in evaluating their own generated questions when compared to those
crafted by other models. On WSC+, GPT-4, the top-performing LLM, achieves an
accuracy of 68.7%, significantly below the human benchmark of 95.1%.
