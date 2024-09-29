---
layout: publication
title: Exploring Design Choices For Building Language45;specific Llms
authors: Tejaswi Atula, Gupta Nilesh, Choi Eunsol
conference: "Arxiv"
year: 2024
bibkey: tejaswi2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14670"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Tools']
---
Despite rapid progress in large language models (LLMs) their performance on a vast majority of languages remain unsatisfactory. In this paper we study building language45;specific LLMs by adapting monolingual and multilingual LLMs. We conduct systematic experiments on how design choices (base model selection vocabulary extension and continued fine45;tuning) impact the adapted LLM both in terms of efficiency (how many tokens are needed to encode the same amount of information) and end task performance. We find that (1) the initial performance before the adaptation is not always indicative of the final performance. (2) Efficiency can easily improved with simple vocabulary extension and continued fine45;tuning in most LLMs we study and (3) The optimal adaptation method is highly language45;dependent and the simplest approach works well across various experimental settings. Adapting English45;centric models can yield better results than adapting multilingual models despite their worse initial performance on low45;resource languages. Together our work lays foundations on efficiently building language45;specific LLMs by adapting existing LLMs.
