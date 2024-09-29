---
layout: publication
title: Adaptive Token Biaser Knowledge Editing Via Biasing Key Entities
authors: Bi Baolong, Liu Shenghua, Wang Yiwei, Mei Lingrui, Gao Hongcheng, Xu Yilong, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: bi2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12468"}
tags: ['Ethics And Bias', 'Prompting']
---
The parametric knowledge memorized by large language models (LLMs) becomes outdated quickly. In45;context editing (ICE) is currently the most effective method for updating the knowledge of LLMs. Recent advancements involve enhancing ICE by modifying the decoding strategy obviating the need for altering internal model structures or adjusting external prompts. However this enhancement operates across the entire sequence generation encompassing a plethora of non45;critical tokens. In this work we introduce textbf123;A125;daptive textbf123;T125;oken textbf123;Bias125;er (textbf123;ATBias125;) a new decoding technique designed to enhance ICE. It focuses on the tokens that are mostly related to knowledge during decoding biasing their logits by matching key entities related to new and parametric knowledge. Experimental results show that ATBias significantly enhances ICE performance achieving up to a 32.337; improvement over state45;of45;the45;art ICE methods while incurring only half the latency. ATBias not only improves the knowledge editing capabilities of ICE but can also be widely applied to LLMs with negligible cost.
