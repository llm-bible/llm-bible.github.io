---
layout: publication
title: 'ACT-MNMT Auto-constriction Turning For Multilingual Neural Machine Translation'
authors: Dai Shaojie, Liu Xin, Luo Ping, Yu Yue
conference: "Arxiv"
year: 2024
bibkey: dai2024act
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06745"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
"Large language model (LLM) has achieved promising performance in multilingual machine translation tasks through zero/few-shot prompts or prompt-tuning. However, due to the mixture of multilingual data during the pre-training of LLM, the LLM-based translation models face the off-target issue in both prompt-based methods, including a series of phenomena, namely instruction misunderstanding, translation with wrong language and over-generation. For this issue, this paper introduces an \textbf\{\underline\{A\}\}uto-\textbf\{\underline\{C\}\}onstriction \textbf\{\underline\{T\}\}urning mechanism for \textbf\{\underline\{M\}\}ultilingual \textbf\{\underline\{N\}\}eural \textbf\{\underline\{M\}\}achine \textbf\{\underline\{T\}\}ranslation (\model), which is a novel supervised fine-tuning mechanism and orthogonal to the traditional prompt-based methods. In this method, \model automatically constructs a constrained template in the target side by adding trigger tokens ahead of the ground truth. Furthermore, trigger tokens can be arranged and combined freely to represent different task semantics, and they can be iteratively updated to maximize the label likelihood. Experiments are performed on WMT test sets with multiple metrics, and the experimental results demonstrate that \model achieves substantially improved performance across multiple translation directions and reduce the off-target phenomena in the translation."
