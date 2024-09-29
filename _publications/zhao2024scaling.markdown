---
layout: publication
title: Longagent Scaling Language Models To 128k Context Through Multi45;agent Collaboration
authors: Zhao Jun, Zu Can, Xu Hao, Lu Yi, He Wei, Ding Yiwen, Gui Tao, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: zhao2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11550"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive performance in understanding language and executing complex reasoning tasks. However LLMs with long context windows have been notorious for their expensive training costs and high inference latency. Even the most advanced models such as GPT45;4 and Claude2 often make mistakes when processing inputs of over 100k tokens a phenomenon also known as textit123;lost in the middle125;. In this paper we propose textsc123;LongAgent125; a method based on multi45;agent collaboration which scales LLMs (e.g. LLaMA) to a context of 128K and demonstrates potential superiority in long45;text processing compared to GPT45;4. In textsc123;LongAgent125; a leader is responsible for understanding user intent and directing team members to acquire information from documents. Due to members hallucinations it is non45;trivial for a leader to obtain accurate information from the responses of dozens to hundreds of members. To address this we develop an textit123;inter45;member communication125; mechanism to resolve response conflicts caused by hallucinations through information sharing. Our experimental results indicate that textsc123;LongAgent125; offers a promising alternative for long45;text processing. The agent team instantiated with LLaMA45;7B achieves significant improvements in tasks such as 128k45;long text retrieval multi45;hop question answering compared to GPT45;4.
