---
layout: publication
title: Defensive Prompt Patch A Robust And Interpretable Defense Of Llms Against Jailbreak Attacks
authors: Xiong Chen, Qi Xiangyu, Chen Pin-yu, Ho Tsung-yi
conference: "Arxiv"
year: 2024
bibkey: xiong2024defensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20099"}
tags: ['Pretraining Methods', 'Prompting', 'Responsible AI', 'Security', 'Tools']
---
Safety security and compliance are essential requirements when aligning large language models (LLMs). However many seemingly aligned LLMs are soon shown to be susceptible to jailbreak attacks. These attacks aim to circumvent the models safety guardrails and security mechanisms by introducing jailbreak prompts into malicious queries. In response to these challenges this paper introduces Defensive Prompt Patch (DPP) a novel prompt45;based defense mechanism specifically designed to protect LLMs against such sophisticated jailbreak strategies. Unlike previous approaches which have often compromised the utility of the model for the sake of safety DPP is designed to achieve a minimal Attack Success Rate (ASR) while preserving the high utility of LLMs. Our method uses strategically designed interpretable suffix prompts that effectively thwart a wide range of standard and adaptive jailbreak techniques. Empirical results conducted on LLAMA45;245;7B45;Chat and Mistral45;7B45;Instruct45;v0.2 models demonstrate the robustness and adaptability of DPP showing significant reductions in ASR with negligible impact on utility. Our approach not only outperforms existing defense strategies in balancing safety and functionality but also provides a scalable and interpretable solution applicable to various LLM platforms.
