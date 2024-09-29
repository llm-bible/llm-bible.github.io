---
layout: publication
title: "Before Generation, Align It! A Novel And Effective Strategy For Mitigating Hallucinations In Text-to-sql Generation"
authors: Qu Ge, Li Jinyang, Li Bowen, Qin Bowen, Huo Nan, Ma Chenhao, Cheng Reynold
conference: "Arxiv"
year: 2024
bibkey: qu2024before
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15307"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Security', 'Tools']
---
Large Language Models (LLMs) driven by In-Context Learning (ICL) have significantly improved the performance of text-to-SQL. Previous methods generally employ a two-stage reasoning framework namely 1) schema linking and 2) logical synthesis making the framework not only effective but also interpretable. Despite these advancements the inherent bad nature of the generalization of LLMs often results in hallucinations which limits the full potential of LLMs. In this work we first identify and categorize the common types of hallucinations at each stage in text-to-SQL. We then introduce a novel strategy Task Alignment (TA) designed to mitigate hallucinations at each stage. TA encourages LLMs to take advantage of experiences from similar tasks rather than starting the tasks from scratch. This can help LLMs reduce the burden of generalization thereby mitigating hallucinations effectively. We further propose TA-SQL a text-to-SQL framework based on this strategy. The experimental results and comprehensive analysis demonstrate the effectiveness and robustness of our framework. Specifically it enhances the performance of the GPT-4 baseline by 21.2337; relatively on BIRD dev and it yields significant improvements across six models and four mainstream complex text-to-SQL benchmarks.
