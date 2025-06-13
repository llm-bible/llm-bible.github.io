---
layout: publication
title: 'Jailbreak-audiobench: In-depth Evaluation And Analysis Of Jailbreak Threats For Large Audio Language Models'
authors: Hao Cheng, Erjia Xiao, Jing Shao, Yichi Wang, Le Yang, Chao Shen, Philip Torr, Jindong Gu, Renjing Xu
conference: "Arxiv"
year: 2025
bibkey: cheng2025jailbreak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13772"}
tags: ['Responsible AI', 'Security', 'Multimodal Models', 'Reinforcement Learning']
---
Large Language Models (LLMs) demonstrate impressive zero-shot performance across a wide range of natural language processing tasks. Integrating various modality encoders further expands their capabilities, giving rise to Multimodal Large Language Models (MLLMs) that process not only text but also visual and auditory modality inputs. However, these advanced capabilities may also pose significant security risks, as models can be exploited to generate harmful or inappropriate content through jailbreak attack. While prior work has extensively explored how manipulating textual or visual modality inputs can circumvent safeguards in LLMs and MLLMs, the vulnerability of audio-specific Jailbreak on Large Audio-Language Models (LALMs) remains largely underexplored. To address this gap, we introduce \textbf\{Jailbreak-AudioBench\}, which consists of the Toolbox, curated Dataset, and comprehensive Benchmark. The Toolbox supports not only text-to-audio conversion but also various editing techniques for injecting audio hidden semantics. The curated Dataset provides diverse explicit and implicit jailbreak audio examples in both original and edited forms. Utilizing this dataset, we evaluate multiple state-of-the-art LALMs and establish the most comprehensive Jailbreak benchmark to date for audio modality. Finally, Jailbreak-AudioBench establishes a foundation for advancing future research on LALMs safety alignment by enabling the in-depth exposure of more powerful jailbreak threats, such as query-based audio editing, and by facilitating the development of effective defense mechanisms.
