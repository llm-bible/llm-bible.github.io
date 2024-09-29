---
layout: publication
title: The Philosophers Stone Trojaning Plugins Of Large Language Models
authors: Dong Tian, Xue Minhui, Chen Guoxing, Holland Rayne, Meng Yan, Li Shaofeng, Liu Zhen, Zhu Haojin
conference: "Arxiv"
year: 2023
bibkey: dong2023trojaning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00374"}
tags: ['Agentic', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Open45;source Large Language Models (LLMs) have recently gained popularity because of their comparable performance to proprietary LLMs. To efficiently fulfill domain45;specialized tasks open45;source LLMs can be refined without expensive accelerators using low45;rank adapters. However it is still unknown whether low45;rank adapters can be exploited to control LLMs. To address this gap we demonstrate that an infected adapter can induce on specific triggersan LLM to output content defined by an adversary and to even maliciously use tools. To train a Trojan adapter we propose two novel attacks POLISHED and FUSION that improve over prior approaches. POLISHED uses a superior LLM to align naively poisoned data based on our insight that it can better inject poisoning knowledge during training. In contrast FUSION leverages a novel over45;poisoning procedure to transform a benign adapter into a malicious one by magnifying the attention between trigger and target in model weights. In our experiments we first conduct two case studies to demonstrate that a compromised LLM agent can use malware to control the system (e.g. a LLM45;driven robot) or to launch a spear45;phishing attack. Then in terms of targeted misinformation we show that our attacks provide higher attack effectiveness than the existing baseline and for the purpose of attracting downloads preserve or improve the adapters utility. Finally we designed and evaluated three potential defenses. However none proved entirely effective in safeguarding against our attacks highlighting the need for more robust defenses supporting a secure LLM supply chain.
