---
layout: publication
title: 'Look Before You Leap: Enhancing Attention And Vigilance Regarding Harmful Content With Guidelinellm'
authors: Shaoqing Zhang, Zhuosheng Zhang, Kehai Chen, Rongxiang Weng, Muyun Yang, Tiejun Zhao, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10423"}
  - {name: "Code", url: "https://github.com/sqzhang-lazy/GuidelineLLM"}
tags: ['Fine-Tuning', 'Responsible AI', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Despite being empowered with alignment mechanisms, large language models
(LLMs) are increasingly vulnerable to emerging jailbreak attacks that can
compromise their alignment mechanisms. This vulnerability poses significant
risks to real-world applications. Existing work faces challenges in both
training efficiency and generalization capabilities (i.e., Reinforcement
Learning from Human Feedback and Red-Teaming). Developing effective strategies
to enable LLMs to resist continuously evolving jailbreak attempts represents a
significant challenge. To address this challenge, we propose a novel defensive
paradigm called GuidelineLLM, which assists LLMs in recognizing queries that
may have harmful content. Before LLMs respond to a query, GuidelineLLM first
identifies potential risks associated with the query, summarizes these risks
into guideline suggestions, and then feeds these guidelines to the responding
LLMs. Importantly, our approach eliminates the necessity for additional safety
fine-tuning of the LLMs themselves; only the GuidelineLLM requires fine-tuning.
This characteristic enhances the general applicability of GuidelineLLM across
various LLMs. Experimental results demonstrate that GuidelineLLM can
significantly reduce the attack success rate (ASR) against LLM (an average
reduction of 34.17% ASR) while maintaining the usefulness of LLM in handling
benign queries. The code is available at
https://github.com/sqzhang-lazy/GuidelineLLM.
