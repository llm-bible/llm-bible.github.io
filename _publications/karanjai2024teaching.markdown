---
layout: publication
title: Teaching Machines To Code&#58; Smart Contract Translation With Llms
authors: Karanjai Rabimba, Xu Lei, Shi Weidong
conference: "Arxiv"
year: 2024
bibkey: karanjai2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09740"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
The advent of large language models (LLMs) has marked a significant milestone in the realm of artificial intelligence with their capabilities often matching or surpassing human expertise in various domains. Among these achievements their adeptness in translation tasks stands out closely mimicking the intricate and preliminary processes undertaken by human translators to ensure the fidelity and quality of the translated content. Despite the advancements in utilizing LLMs for translating programming code across different languages the domain of smart contract translation particularly into languages not previously encountered by the LLM remains largely unexplored. In our research we present a pioneering approach SolMover which harnesses the synergy of two distinct LLMs within a unified framework. This framework is designed to grasp coding principles and apply this understanding to the translation of code into an unfamiliar language. Our study delves into the capacity of LLMs to mimic human learning processes offering an in-depth evaluation of our methodology for converting smart contracts written in Solidity to Move a language with limited resources. The framework employs one LLM to decipher coding conventions for the new language creating a blueprint for the second LLM which lacking planning abilities possesses coding expertise. The empirical evidence from our experiments suggests that SolMover substantially enhances performance compared to gpt-3.5-turbo-1106 and achieves superior results over competitors such as Palm2 and Mixtral-8x7B-Instruct. Additionally our analysis highlights the efficacy of our bug mitigation strategy in elevating code quality across all models even outside the SolMover framework.
