---
layout: publication
title: GradSafe Detecting Jailbreak Prompts for LLMs via Safety-Critical Gradient Analysis
authors: Xie Yueqi, Fang Minghong, Pi Renjie, Gong Neil
conference: "Arxiv"
year: 2024
bibkey: xie2024gradsafe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13494"}
  - {name: "Code", url: "https://github.com/xyq7/GradSafe"}
tags: ['ARXIV', 'Has Code', 'Pretraining Methods', 'Prompt', 'Tools']
---
Large Language Models (LLMs) face threats from jailbreak prompts. Existing methods for detecting jailbreak prompts are primarily online moderation APIs or finetuned LLMs. These strategies however often require extensive and resource-intensive data collection and training processes. In this study we propose GradSafe which effectively detects jailbreak prompts by scrutinizing the gradients of safety-critical parameters in LLMs. Our method is grounded in a pivotal observation the gradients of an LLMs loss for jailbreak prompts paired with compliance response exhibit similar patterns on certain safety-critical parameters. In contrast safe prompts lead to different gradient patterns. Building on this observation GradSafe analyzes the gradients from prompts (paired with compliance responses) to accurately detect jailbreak prompts. We show that GradSafe applied to Llama-2 without further training outperforms Llama Guard despite its extensive finetuning with a large dataset in detecting jailbreak prompts. This superior performance is consistent across both zero-shot and adaptation scenarios as evidenced by our evaluations on ToxicChat and XSTest. The source code is available at https://github.com/xyq7/GradSafe.
