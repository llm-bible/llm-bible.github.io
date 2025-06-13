---
layout: publication
title: 'Attention Tracker: Detecting Prompt Injection Attacks In Llms'
authors: Kuo-han Hung, Ching-yun Ko, Ambrish Rawat, I-hsin Chung, Winston H. Hsu, Pin-yu Chen
conference: "Arxiv"
year: 2024
bibkey: hung2024attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00348'}
tags: ['Attention Mechanism', 'Security', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) have revolutionized various domains but remain
vulnerable to prompt injection attacks, where malicious inputs manipulate the
model into ignoring original instructions and executing designated action. In
this paper, we investigate the underlying mechanisms of these attacks by
analyzing the attention patterns within LLMs. We introduce the concept of the
distraction effect, where specific attention heads, termed important heads,
shift focus from the original instruction to the injected instruction. Building
on this discovery, we propose Attention Tracker, a training-free detection
method that tracks attention patterns on instruction to detect prompt injection
attacks without the need for additional LLM inference. Our method generalizes
effectively across diverse models, datasets, and attack types, showing an AUROC
improvement of up to 10.0% over existing methods, and performs well even on
small LLMs. We demonstrate the robustness of our approach through extensive
evaluations and provide insights into safeguarding LLM-integrated systems from
prompt injection vulnerabilities.
