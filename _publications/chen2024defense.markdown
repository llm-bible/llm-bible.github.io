---
layout: publication
title: 'Bathe: Defense Against The Jailbreak Attack In Multimodal Large Language Models By Treating Harmful Instruction As Backdoor Trigger'
authors: Yulin Chen, Haoran Li, Yirui Zhang, Zihao Zheng, Yangqiu Song, Bryan Hooi
conference: "Arxiv"
year: 2024
bibkey: chen2024defense
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.09093'}
tags: ['Reinforcement Learning', 'Prompting', 'Security', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) have showcased impressive
performance in a variety of multimodal tasks. On the other hand, the
integration of additional image modality may allow the malicious users to
inject harmful content inside the images for jailbreaking. Unlike text-based
LLMs, where adversaries need to select discrete tokens to conceal their
malicious intent using specific algorithms, the continuous nature of image
signals provides a direct opportunity for adversaries to inject harmful
intentions. In this work, we propose \\(\textbf\{BaThe\}\\) (\\(\textbf\{Ba\}\\)ckdoor
\\(\textbf\{T\}\\)rigger S\\(\textbf\{h\}\\)i\\(\textbf\{e\}\\)ld), a simple yet effective
jailbreak defense mechanism. Our work is motivated by recent research on
jailbreak backdoor attack and virtual prompt backdoor attack in generative
language models. Jailbreak backdoor attack uses harmful instructions combined
with manually crafted strings as triggers to make the backdoored model generate
prohibited responses. We assume that harmful instructions can function as
triggers, and if we alternatively set rejection responses as the triggered
response, the backdoored model then can defend against jailbreak attacks. We
achieve this by utilizing virtual rejection prompt, similar to the virtual
prompt backdoor attack. We embed the virtual rejection prompt into the soft
text embeddings, which we call ``wedge''. Our comprehensive experiments
demonstrate that BaThe effectively mitigates various types of jailbreak attacks
and is adaptable to defend against unseen attacks, with minimal impact on
MLLMs' performance.
