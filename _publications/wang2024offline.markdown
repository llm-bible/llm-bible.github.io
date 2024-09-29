---
layout: publication
title: Offline RLHF Methods Need More Accurate Supervision Signals
authors: Wang Shiqi, Zhang Zhengze, Zhao Rui, Tan Fei, Nguyen Cam Tu
conference: "Arxiv"
year: 2024
bibkey: wang2024offline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09385"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools']
---
With the rapid advances in Large Language Models (LLMs) aligning LLMs with human preferences become increasingly important. Although Reinforcement Learning with Human Feedback (RLHF) proves effective it is complicated and highly resource45;intensive. As such offline RLHF has been introduced as an alternative solution which directly optimizes LLMs with ranking losses on a fixed preference dataset. Current offline RLHF only captures the ordinal relationship between responses overlooking the crucial aspect of how much one is preferred over the others. To address this issue we propose a simple yet effective solution called textbf123;R125;eward textbf123;D125;ifference textbf123;O125;ptimization shorted as textbf123;RDO125;. Specifically we introduce 123;it reward difference coefficients125; to reweigh sample pairs in offline RLHF. We then develop a 123;it difference model125; involving rich interactions between a pair of responses for predicting these difference coefficients. Experiments with 7B LLMs on the HH and TL;DR datasets substantiate the effectiveness of our method in both automatic metrics and human evaluation thereby highlighting its potential for aligning LLMs with human intent and values.
