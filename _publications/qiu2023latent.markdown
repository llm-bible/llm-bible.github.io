---
layout: publication
title: Latent Jailbreak A Benchmark For Evaluating Text Safety And Output Robustness Of Large Language Models
authors: Qiu Huachuan, Zhang Shuai, Li Anqi, He Hongliang, Lan Zhenzhong
conference: "Arxiv"
year: 2023
bibkey: qiu2023latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.08487"}
  - {name: "Code", url: "https://github.com/qiuhuachuan/latent-jailbreak"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Security', 'Tools']
---
Considerable research efforts have been devoted to ensuring that large language models (LLMs) align with human values and generate safe text. However an excessive focus on sensitivity to certain topics can compromise the models robustness in following instructions thereby impacting its overall performance in completing tasks. Previous benchmarks for jailbreaking LLMs have primarily focused on evaluating the safety of the models without considering their robustness. In this paper we propose a benchmark that assesses both the safety and robustness of LLMs emphasizing the need for a balanced approach. To comprehensively study text safety and output robustness we introduce a latent jailbreak prompt dataset each involving malicious instruction embedding. Specifically we instruct the model to complete a regular task such as translation with the text to be translated containing malicious instructions. To further analyze safety and robustness we design a hierarchical annotation framework. We present a systematic analysis of the safety and robustness of LLMs regarding the position of explicit normal instructions word replacements (verbs in explicit normal instructions target groups in malicious instructions cue words for explicit normal instructions) and instruction replacements (different explicit normal instructions). Our results demonstrate that current LLMs not only prioritize certain instruction verbs but also exhibit varying jailbreak rates for different instruction verbs in explicit normal instructions. Code and data are available at https://github.com/qiuhuachuan/latent-jailbreak."
