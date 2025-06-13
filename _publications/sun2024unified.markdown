---
layout: publication
title: 'Llm4vuln: A Unified Evaluation Framework For Decoupling And Enhancing Llms'' Vulnerability Reasoning'
authors: Yuqiang Sun, Daoyuan Wu, Yue Xue, Han Liu, Wei Ma, Lyuye Zhang, Yang Liu, Yingjiu Li
conference: "Arxiv"
year: 2024
bibkey: sun2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16185"}
tags: ['Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Large language models (LLMs) have demonstrated significant potential in
various tasks, including those requiring human-level intelligence, such as
vulnerability detection. However, recent efforts to use LLMs for vulnerability
detection remain preliminary, as they lack a deep understanding of whether a
subject LLM's vulnerability reasoning capability stems from the model itself or
from external aids such as knowledge retrieval and tooling support.
  In this paper, we aim to decouple LLMs' vulnerability reasoning from other
capabilities, such as vulnerability knowledge adoption, context information
retrieval, and advanced prompt schemes. We introduce LLM4Vuln, a unified
evaluation framework that separates and assesses LLMs' vulnerability reasoning
capabilities and examines improvements when combined with other enhancements.
  We conduct controlled experiments using 147 ground-truth vulnerabilities and
147 non-vulnerable cases in Solidity, Java and C/C++, testing them in a total
of 3,528 scenarios across four LLMs (GPT-3.5, GPT-4, Phi-3, and Llama 3). Our
findings reveal the varying impacts of knowledge enhancement, context
supplementation, and prompt schemes. We also identify 14 zero-day
vulnerabilities in four pilot bug bounty programs, resulting in $3,576 in
bounties.
