---
layout: publication
title: Decomposed Prompting&#58; Unveiling Multilingual Linguistic Structure Knowledge In English-centric Large Language Models
authors: Nie Ercong, Yuan Shuzhou, Ma Bolei, Schmid Helmut, Färber Michael, Kreuter Frauke, Schütze Hinrich
conference: "Arxiv"
year: 2024
bibkey: nie2024decomposed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18397"}
tags: ['Efficiency And Optimization', 'Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Despite the predominance of English in their training data English-centric Large Language Models (LLMs) like GPT-3 and LLaMA display a remarkable ability to perform multilingual tasks raising questions about the depth and nature of their cross-lingual capabilities. This paper introduces the decomposed prompting approach to probe the linguistic structure understanding of these LLMs in sequence labeling tasks. Diverging from the single text-to-text prompt our method generates for each token of the input sentence an individual prompt which asks for its linguistic label. We assess our method on the Universal Dependencies part-of-speech tagging dataset for 38 languages utilizing both English-centric and multilingual LLMs. Our findings show that decomposed prompting surpasses the iterative prompting baseline in efficacy and efficiency under zero- and few-shot settings. Further analysis reveals the influence of evaluation methods and the use of instructions in prompts. Our multilingual investigation shows that English-centric language models perform better on average than multilingual models. Our study offers insights into the multilingual transferability of English-centric LLMs contributing to the understanding of their multilingual linguistic knowledge.
