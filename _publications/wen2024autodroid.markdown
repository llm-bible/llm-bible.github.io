---
layout: publication
title: 'Autodroid-v2: Boosting Slm-based GUI Agents Via Code Generation'
authors: Hao Wen, Shizuo Tian, Borislav Pavlov, Wenjie Du, Yixuan Li, Ge Chang, Shanhui Zhao, Jiacheng Liu, Yunxin Liu, Ya-qin Zhang, Yuanchun Li
conference: "Arxiv"
year: 2024
bibkey: wen2024autodroid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18116"}
  - {name: "Code", url: "https://github.com/MobileLLM/AutoDroid-V2"}
tags: ['Agentic', 'Applications', 'Has Code', 'Tools']
---
Large language models (LLMs) have brought exciting new advances to mobile UI
agents, a long-standing research field that aims to complete arbitrary natural
language tasks through mobile UI interactions. However, existing UI agents
usually demand powerful large language models that are difficult to be deployed
locally on end-users' devices, raising huge concerns about user privacy and
centralized serving cost. Inspired by the remarkable coding abilities of recent
small language models (SLMs), we propose to convert the UI task automation
problem to a code generation problem, which can be effectively solved by an
on-device SLM and efficiently executed with an on-device code interpreter.
Unlike normal coding tasks that can be extensively pre-trained with public
datasets, generating UI automation code is challenging due to the diversity,
complexity, and variability of target apps. Therefore, we adopt a
document-centered approach that automatically builds fine-grained API
documentation for each app and generates diverse task samples based on this
documentation. By guiding the agent with the synthetic documents and task
samples, it learns to generate precise and efficient scripts to complete unseen
tasks. Based on detailed comparisons with state-of-the-art mobile UI agents,
our approach effectively improves the mobile task automation with significantly
higher success rates and lower latency/token consumption. Code is open-sourced
at https://github.com/MobileLLM/AutoDroid-V2.
