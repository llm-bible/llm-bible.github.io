---
layout: publication
title: 'Privacy And Security Threat For Openai Gpts'
authors: Wei Wenying, Zhao Kaifa, Xue Lei, Fan Ming
conference: "Arxiv"
year: 2025
bibkey: wenying2025privacy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04036"}
tags: ['Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Large language models (LLMs) demonstrate powerful information handling capabilities and are widely integrated into chatbot applications. OpenAI provides a platform for developers to construct custom GPTs, extending ChatGPT's functions and integrating external services. Since its release in November 2023, over 3 million custom GPTs have been created. However, such a vast ecosystem also conceals security and privacy threats. For developers, instruction leaking attacks threaten the intellectual property of instructions in custom GPTs through carefully crafted adversarial prompts. For users, unwanted data access behavior by custom GPTs or integrated third-party services raises significant privacy concerns. To systematically evaluate the scope of threats in real-world LLM applications, we develop three phases instruction leaking attacks target GPTs with different defense level. Our widespread experiments on 10,000 real-world custom GPTs reveal that over 98.8% of GPTs are vulnerable to instruction leaking attacks via one or more adversarial prompts, and half of the remaining GPTs can also be attacked through multiround conversations. We also developed a framework to assess the effectiveness of defensive strategies and identify unwanted behaviors in custom GPTs. Our findings show that 77.5% of custom GPTs with defense strategies are vulnerable to basic instruction leaking attacks. Additionally, we reveal that 738 custom GPTs collect user conversational information, and identified 8 GPTs exhibiting data access behaviors that are unnecessary for their intended functionalities. Our findings raise awareness among GPT developers about the importance of integrating specific defensive strategies in their instructions and highlight users' concerns about data privacy when using LLM-based applications.
