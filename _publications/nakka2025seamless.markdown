---
layout: publication
title: 'Litelmguard: Seamless And Lightweight On-device Prompt Filtering For Safeguarding Small Language Models Against Quantization-induced Risks And Vulnerabilities'
authors: Kalyan Nakka, Jimmy Dani, Ausmit Mondal, Nitesh Saxena
conference: "Arxiv"
year: 2025
bibkey: nakka2025seamless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05619"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Fairness', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Bias Mitigation', 'Quantization', 'Ethics and Bias', 'Prompting']
---
The growing adoption of Large Language Models (LLMs) has influenced the development of their lighter counterparts-Small Language Models (SLMs)-to enable on-device deployment across smartphones and edge devices. These SLMs offer enhanced privacy, reduced latency, server-free functionality, and improved user experience. However, due to resource constraints of on-device environment, SLMs undergo size optimization through compression techniques like quantization, which can inadvertently introduce fairness, ethical and privacy risks. Critically, quantized SLMs may respond to harmful queries directly, without requiring adversarial manipulation, raising significant safety and trust concerns.
  To address this, we propose LiteLMGuard (LLMG), an on-device prompt guard that provides real-time, prompt-level defense for quantized SLMs. Additionally, our prompt guard is designed to be model-agnostic such that it can be seamlessly integrated with any SLM, operating independently of underlying architectures. Our LLMG formalizes prompt filtering as a deep learning (DL)-based prompt answerability classification task, leveraging semantic understanding to determine whether a query should be answered by any SLM. Using our curated dataset, Answerable-or-Not, we trained and fine-tuned several DL models and selected ELECTRA as the candidate, with 97.75% answerability classification accuracy.
  Our safety effectiveness evaluations demonstrate that LLMG defends against over 87% of harmful prompts, including both direct instruction and jailbreak attack strategies. We further showcase its ability to mitigate the Open Knowledge Attacks, where compromised SLMs provide unsafe responses without adversarial prompting. In terms of prompt filtering effectiveness, LLMG achieves near state-of-the-art filtering accuracy of 94%, with an average latency of 135 ms, incurring negligible overhead for users.
