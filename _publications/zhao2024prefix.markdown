---
layout: publication
title: 'Prefix Guidance: A Steering Wheel For Large Language Models To Defend Against Jailbreak Attacks'
authors: Zhao Jiawei, Chen Kejiang, Yuan Xiaojian, Zhang Weiming
conference: "Arxiv"
year: 2024
bibkey: zhao2024prefix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08924"}
  - {name: "Code", url: "https://github.com/weiyezhimeng/Prefix-Guidance"}
tags: ['Has Code', 'Prompting', 'RAG', 'Security', 'Tools']
---
In recent years, the rapid development of large language models (LLMs) has
achieved remarkable performance across various tasks. However, research
indicates that LLMs are vulnerable to jailbreak attacks, where adversaries can
induce the generation of harmful content through meticulously crafted prompts.
This vulnerability poses significant challenges to the secure use and promotion
of LLMs. Existing defense methods offer protection from different perspectives
but often suffer from insufficient effectiveness or a significant impact on the
model's capabilities. In this paper, we propose a plug-and-play and
easy-to-deploy jailbreak defense framework, namely Prefix Guidance (PG), which
guides the model to identify harmful prompts by directly setting the first few
tokens of the model's output. This approach combines the model's inherent
security capabilities with an external classifier to defend against jailbreak
attacks. We demonstrate the effectiveness of PG across three models and five
attack methods. Compared to baselines, our approach is generally more effective
on average. Additionally, results on the Just-Eval benchmark further confirm
PG's superiority to preserve the model's performance. our code is available at
https://github.com/weiyezhimeng/Prefix-Guidance.
