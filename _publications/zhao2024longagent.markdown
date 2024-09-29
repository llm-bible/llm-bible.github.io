---
layout: publication
title: LongAgent Scaling Language Models to 128k Context through Multi-Agent Collaboration
authors: Zhao Jun, Zu Can, Xu Hao, Lu Yi, He Wei, Ding Yiwen, Gui Tao, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: zhao2024longagent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11550"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive performance in understanding language and executing complex reasoning tasks. However LLMs with long context windows have been notorious for their expensive training costs and high inference latency. Even the most advanced models such as GPT-4 and Claude2 often make mistakes when processing inputs of over 100k tokens a phenomenon also known as . In this paper we propose a method based on multi-agent collaboration which scales LLMs (e.g. LLaMA) to a context of 128K and demonstrates potential superiority in long-text processing compared to GPT-4. In a leader is responsible for understanding user intent and directing team members to acquire information from documents. Due to members hallucinations it is non-trivial for a leader to obtain accurate information from the responses of dozens to hundreds of members. To address this we develop an mechanism to resolve response conflicts caused by hallucinations through information sharing. Our experimental results indicate that offers a promising alternative for long-text processing. The agent team instantiated with LLaMA-7B achieves significant improvements in tasks such as 128k-long text retrieval multi-hop question answering compared to GPT-4.
