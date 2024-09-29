---
layout: publication
title: "Quantitative Certification Of Bias In Large Language Models"
authors: Chaudhary Isha, Hu Qian, Kumar Manoj, Ziyadi Morteza, Gupta Rahul, Singh Gagandeep
conference: "Arxiv"
year: 2024
bibkey: chaudhary2024quantitative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18780"}
tags: ['Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) can produce responses that exhibit social biases and support stereotypes. However conventional benchmarking is insufficient to thoroughly evaluate LLM bias as it can not scale to large sets of prompts and provides no guarantees. Therefore we propose a novel certification framework QuaCer-B (Quantitative Certification of Bias) that provides formal guarantees on obtaining unbiased responses from target LLMs under large sets of prompts. A certificate consists of high-confidence bounds on the probability of obtaining biased responses from the LLM for any set of prompts containing sensitive attributes sampled from a distribution. We illustrate the bias certification in LLMs for prompts with various prefixes drawn from given distributions. We consider distributions of random token sequences mixtures of manual jailbreaks and jailbreaks in the LLMs embedding space to certify its bias. We certify popular LLMs with QuaCer-B and present novel insights into their biases.
