---
layout: publication
title: Towards A Mechanistic Interpretation Of Multi45;step Reasoning Capabilities Of Language Models
authors: Hou Yifan, Li Jiaoda, Fei Yu, Stolfo Alessandro, Zhou Wangchunshu, Zeng Guangtao, Bosselut Antoine, Sachan Mrinmaya
conference: "Arxiv"
year: 2023
bibkey: hou2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14491"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent work has shown that language models (LMs) have strong multi45;step (i.e. procedural) reasoning capabilities. However it is unclear whether LMs perform these tasks by cheating with answers memorized from pretraining corpus or via a multi45;step reasoning mechanism. In this paper we try to answer this question by exploring a mechanistic interpretation of LMs for multi45;step reasoning tasks. Concretely we hypothesize that the LM implicitly embeds a reasoning tree resembling the correct reasoning process within it. We test this hypothesis by introducing a new probing approach (called MechanisticProbe) that recovers the reasoning tree from the models attention patterns. We use our probe to analyze two LMs GPT45;2 on a synthetic task (k45;th smallest element) and LLaMA on two simple language45;based reasoning tasks (ProofWriter amp; AI2 Reasoning Challenge). We show that MechanisticProbe is able to detect the information of the reasoning tree from the models attentions for most examples suggesting that the LM indeed is going through a process of multi45;step reasoning within its architecture in many cases.
