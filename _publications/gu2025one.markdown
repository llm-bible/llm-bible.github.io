---
layout: publication
title: 'One Trigger Token Is Enough: A Defense Strategy For Balancing Safety And Usability In Large Language Models'
authors: Haoran Gu, Handing Wang, Yi Mei, Mengjie Zhang, Yaochu Jin
conference: "Arxiv"
year: 2025
bibkey: gu2025one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07167"}
tags: ['Responsible AI', 'Security', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have been extensively used across diverse domains, including virtual assistants, automated code generation, and scientific research. However, they remain vulnerable to jailbreak attacks, which manipulate the models into generating harmful responses despite safety alignment. Recent studies have shown that current safety-aligned LLMs often undergo the shallow safety alignment, where the first few tokens largely determine whether the response will be harmful. Through comprehensive observations, we find that safety-aligned LLMs and various defense strategies generate highly similar initial tokens in their refusal responses, which we define as safety trigger tokens. Building on this insight, we propose \texttt\{D-STT\}, a simple yet effective defense algorithm that identifies and explicitly decodes safety trigger tokens of the given safety-aligned LLM to trigger the model's learned safety patterns. In this process, the safety trigger is constrained to a single token, which effectively preserves model usability by introducing minimum intervention in the decoding process. Extensive experiments across diverse jailbreak attacks and benign prompts demonstrate that \ours significantly reduces output harmfulness while preserving model usability and incurring negligible response time overhead, outperforming ten baseline methods.
