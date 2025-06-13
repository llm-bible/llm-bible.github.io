---
layout: publication
title: 'Defending Against Indirect Prompt Injection By Instruction Detection'
authors: Tongyu Wen, Chenglong Wang, Xiyuan Yang, Haoyu Tang, Yueqi Xie, Lingjuan Lyu, Zhicheng Dou, Fangzhao Wu
conference: "Arxiv"
year: 2025
bibkey: wen2025defending
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06311'}
tags: ['RAG', 'Security', 'Prompting']
---
The integration of Large Language Models (LLMs) with external sources is becoming increasingly common, with Retrieval-Augmented Generation (RAG) being a prominent example. However, this integration introduces vulnerabilities of Indirect Prompt Injection (IPI) attacks, where hidden instructions embedded in external data can manipulate LLMs into executing unintended or harmful actions. We recognize that the success of IPI attacks fundamentally relies in the presence of instructions embedded within external content, which can alter the behavioral state of LLMs. Can effectively detecting such state changes help us defend against IPI attacks? In this paper, we propose a novel approach that takes external data as input and leverages the behavioral state of LLMs during both forward and backward propagation to detect potential IPI attacks. Specifically, we demonstrate that the hidden states and gradients from intermediate layers provide highly discriminative features for instruction detection. By effectively combining these features, our approach achieves a detection accuracy of 99.60% in the in-domain setting and 96.90% in the out-of-domain setting, while reducing the attack success rate to just 0.12% on the BIPIA benchmark.
