---
layout: publication
title: Detecting Language Model Attacks With Perplexity
authors: Alon Gabriel, Kamfonas Michael
conference: "Arxiv"
year: 2023
bibkey: alon2023detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14132"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security']
---
A novel hack involving Large Language Models (LLMs) has emerged exploiting adversarial suffixes to deceive models into generating perilous responses. Such jailbreaks can trick LLMs into providing intricate instructions to a malicious user for creating explosives orchestrating a bank heist or facilitating the creation of offensive content. By evaluating the perplexity of queries with adversarial suffixes using an open45;source LLM (GPT45;2) we found that they have exceedingly high perplexity values. As we explored a broad range of regular (non45;adversarial) prompt varieties we concluded that false positives are a significant challenge for plain perplexity filtering. A Light45;GBM trained on perplexity and token length resolved the false positives and correctly detected most adversarial attacks in the test set.
