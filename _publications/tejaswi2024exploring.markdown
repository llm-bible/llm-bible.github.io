---
layout: publication
title: Exploring Design Choices for Building Language-Specific LLMs
authors: Tejaswi Atula, Gupta Nilesh, Choi Eunsol
conference: "Arxiv"
year: 2024
bibkey: tejaswi2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14670"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Despite rapid progress in large language models (LLMs) their performance on a vast majority of languages remain unsatisfactory. In this paper we study building language-specific LLMs by adapting monolingual and multilingual LLMs. We conduct systematic experiments on how design choices (base model selection vocabulary extension and continued fine-tuning) impact the adapted LLM both in terms of efficiency (how many tokens are needed to encode the same amount of information) and end task performance. We find that (1) the initial performance before the adaptation is not always indicative of the final performance. (2) Efficiency can easily improved with simple vocabulary extension and continued fine-tuning in most LLMs we study and (3) The optimal adaptation method is highly language-dependent and the simplest approach works well across various experimental settings. Adapting English-centric models can yield better results than adapting multilingual models despite their worse initial performance on low-resource languages. Together our work lays foundations on efficiently building language-specific LLMs by adapting existing LLMs.
