---
layout: publication
title: 'Jailbreakv: A Benchmark For Assessing The Robustness Of Multimodal Large Language Models Against Jailbreak Attacks'
authors: Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao
conference: "Arxiv"
year: 2024
bibkey: luo2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03027"}
tags: ['Security', 'Tools', 'Multimodal Models', 'Prompting']
---
With the rapid advancements in Multimodal Large Language Models (MLLMs),
securing these models against malicious inputs while aligning them with human
values has emerged as a critical challenge. In this paper, we investigate an
important and unexplored question of whether techniques that successfully
jailbreak Large Language Models (LLMs) can be equally effective in jailbreaking
MLLMs. To explore this issue, we introduce JailBreakV-28K, a pioneering
benchmark designed to assess the transferability of LLM jailbreak techniques to
MLLMs, thereby evaluating the robustness of MLLMs against diverse jailbreak
attacks. Utilizing a dataset of 2, 000 malicious queries that is also proposed
in this paper, we generate 20, 000 text-based jailbreak prompts using advanced
jailbreak attacks on LLMs, alongside 8, 000 image-based jailbreak inputs from
recent MLLMs jailbreak attacks, our comprehensive dataset includes 28, 000 test
cases across a spectrum of adversarial scenarios. Our evaluation of 10
open-source MLLMs reveals a notably high Attack Success Rate (ASR) for attacks
transferred from LLMs, highlighting a critical vulnerability in MLLMs that
stems from their text-processing capabilities. Our findings underscore the
urgent need for future research to address alignment vulnerabilities in MLLMs
from both textual and visual inputs.
