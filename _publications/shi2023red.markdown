---
layout: publication
title: 'Red Teaming Language Model Detectors With Language Models'
authors: Zhouxing Shi, Yihan Wang, Fan Yin, Xiangning Chen, Kai-wei Chang, Cho-jui Hsieh
conference: "Arxiv"
year: 2023
bibkey: shi2023red
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19713"}
tags: ['Responsible AI', 'Security', 'Prompting', 'RAG']
---
The prevalence and strong capability of large language models (LLMs) present
significant safety and ethical risks if exploited by malicious users. To
prevent the potentially deceptive usage of LLMs, recent works have proposed
algorithms to detect LLM-generated text and protect LLMs. In this paper, we
investigate the robustness and reliability of these LLM detectors under
adversarial attacks. We study two types of attack strategies: 1) replacing
certain words in an LLM's output with their synonyms given the context; 2)
automatically searching for an instructional prompt to alter the writing style
of the generation. In both strategies, we leverage an auxiliary LLM to generate
the word replacements or the instructional prompt. Different from previous
works, we consider a challenging setting where the auxiliary LLM can also be
protected by a detector. Experiments reveal that our attacks effectively
compromise the performance of all detectors in the study with plausible
generations, underscoring the urgent need to improve the robustness of
LLM-generated text detection systems.
