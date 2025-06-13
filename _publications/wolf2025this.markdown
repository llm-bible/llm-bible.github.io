---
layout: publication
title: 'This Is Your Doge, If It Please You: Exploring Deception And Robustness In Mixture Of Llms'
authors: Lorenz Wolf, Sangwoong Yoon, Ilija Bogunovic
conference: "Arxiv"
year: 2025
bibkey: wolf2025this
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05856"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Model Architecture', 'Survey Paper', 'RAG']
---
Mixture of large language model (LLMs) Agents (MoA) architectures achieve
state-of-the-art performance on prominent benchmarks like AlpacaEval 2.0 by
leveraging the collaboration of multiple LLMs at inference time. Despite these
successes, an evaluation of the safety and reliability of MoA is missing. We
present the first comprehensive study of MoA's robustness against deceptive LLM
agents that deliberately provide misleading responses. We examine factors like
the propagation of deceptive information, model size, and information
availability, and uncover critical vulnerabilities. On AlpacaEval 2.0, the
popular LLaMA 3.1-70B model achieves a length-controlled Win Rate (LC WR) of
49.2% when coupled with 3-layer MoA (6 LLM agents). However, we demonstrate
that introducing only a \\(\textit\{single\}\\) carefully-instructed deceptive agent
into the MoA can reduce performance to 37.9%, effectively nullifying all MoA
gains. On QuALITY, a multiple-choice comprehension task, the impact is also
severe, with accuracy plummeting by a staggering 48.5%. Inspired in part by the
historical Doge of Venice voting process, designed to minimize influence and
deception, we propose a range of unsupervised defense mechanisms that recover
most of the lost performance.
