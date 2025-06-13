---
layout: publication
title: 'Investigating The Efficacy Of Large Language Models For Code Clone Detection'
authors: Mohamad Khajezade, Jie Jw Wu, Fatemeh Hendijani Fard, Gema Rodríguez-pérez, Mohamed Sami Shehata
conference: "Arxiv"
year: 2024
bibkey: khajezade2024investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.13802'}
tags: ['Few-Shot', 'Model Architecture', 'GPT', 'Prompting', 'Fine-Tuning']
---
Large Language Models (LLMs) have demonstrated remarkable success in various
natural language processing and software engineering tasks, such as code
generation. The LLMs are mainly utilized in the prompt-based zero/few-shot
paradigm to guide the model in accomplishing the task. GPT-based models are one
of the popular ones studied for tasks such as code comment generation or test
generation. These tasks are `generative' tasks. However, there is limited
research on the usage of LLMs for `non-generative' tasks such as classification
using the prompt-based paradigm. In this preliminary exploratory study, we
investigated the applicability of LLMs for Code Clone Detection (CCD), a
non-generative task. By building a mono-lingual and cross-lingual CCD dataset
derived from CodeNet, we first investigated two different prompts using ChatGPT
to detect Type-4 code clones in Java-Java and Java-Ruby pairs in a zero-shot
setting. We then conducted an analysis to understand the strengths and
weaknesses of ChatGPT in CCD. ChatGPT surpasses the baselines in cross-language
CCD attaining an F1-score of 0.877 and achieves comparable performance to fully
fine-tuned models for mono-lingual CCD, with an F1-score of 0.878. Also, the
prompt and the difficulty level of the problems has an impact on the
performance of ChatGPT. Finally we provide insights and future directions based
on our initial analysis
