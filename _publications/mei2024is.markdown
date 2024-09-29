---
layout: publication
title: ""not Aligned" Is Not "malicious": Being Careful About Hallucinations Of Large Language Models' Jailbreak"
authors: Mei Lingrui, Liu Shenghua, Wang Yiwei, Bi Baolong, Mao Jiayi, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: mei2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11668"}
tags: ['Ethics And Bias', 'Prompting', 'Responsible AI', 'Tools']
---
Jailbreak is a major safety concern of Large Language Models (LLMs) which occurs when malicious prompts lead LLMs to produce harmful outputs raising issues about the reliability and safety of LLMs. Therefore an effective evaluation of jailbreaks is very crucial to develop its mitigation strategies. However our research reveals that many jailbreaks identified by current evaluations may actually be hallucinations-erroneous outputs that are mistaken for genuine safety breaches. This finding suggests that some perceived vulnerabilities might not represent actual threats indicating a need for more precise red teaming benchmarks. To address this problem we propose the (textbfB)enchmark for reli(textbfAB)ilit(textbfY) and jail(textbfB)reak ha(textbfL)l(textbfU)cination (textbfE)valuation (BabyBLUE). BabyBLUE introduces a specialized validation framework including various evaluators to enhance existing jailbreak benchmarks ensuring outputs are useful malicious instructions. Additionally BabyBLUE presents a new dataset as an augmentation to the existing red teaming benchmarks specifically addressing hallucinations in jailbreaks aiming to evaluate the true potential of jailbroken LLM outputs to cause harm to human society.
