---
layout: publication
title: 'Assessing Judging Bias In Large Reasoning Models: An Empirical Study'
authors: Qian Wang, Zhanzhi Lou, Zhenheng Tang, Nuo Chen, Xuandong Zhao, Wenxuan Zhang, Dawn Song, Bingsheng He
conference: "Arxiv"
year: 2025
bibkey: wang2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09946"}
tags: ['Tools', 'Ethics and Bias', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large Reasoning Models (LRMs) like DeepSeek-R1 and OpenAI-o1 have
demonstrated remarkable reasoning capabilities, raising important questions
about their biases in LLM-as-a-judge settings. We present a comprehensive
benchmark comparing judging biases between LLMs and LRMs across both subjective
preference-alignment datasets and objective fact-based datasets. Through
investigation of bandwagon, authority, position, and distraction biases, we
uncover four key findings: (1) despite their advanced reasoning capabilities,
LRMs remain susceptible to the above biases; (2) LRMs demonstrate better
robustness than LLMs specifically on fact-related datasets; (3) LRMs exhibit
notable position bias, preferring options in later positions; and (4) we
identify a novel "superficial reflection bias" where phrases mimicking
reasoning (e.g., "wait, let me think...") significantly influence model
judgments. To address these biases, we design and evaluate three mitigation
strategies: specialized system prompts that reduce judging biases by up to 19%
in preference alignment datasets and 14% in fact-related datasets, in-context
learning that provides up to 27% improvement on preference tasks but shows
inconsistent results on factual tasks, and a self-reflection mechanism that
reduces biases by up to 10% in preference datasets and 16% in fact-related
datasets, with self-reflection proving particularly effective for LRMs. Our
work provides crucial insights for developing more reliable LLM-as-a-Judge
frameworks, especially as LRMs become increasingly deployed as automated
judges.
