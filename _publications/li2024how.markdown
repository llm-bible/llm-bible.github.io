---
layout: publication
title: How Do Humans Write Code Large Models Do It The Same Way Too
authors: Li Long, He Xuzheng
conference: "Arxiv"
year: 2024
bibkey: li2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15729"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Program-of-Thought (PoT) replaces natural language-based Chain-of-Thought (CoT) as the most popular method in Large Language Models (LLMs) mathematical reasoning tasks by utilizing external tool calls to circumvent computational errors. However our evaluation of the GPT-4 and Llama series reveals that using PoT introduces more reasoning errors such as incorrect formulas or flawed logic compared to CoT. To address this issue we propose Human-Think Language (HTL) which leverages a suite of strategies that help integrate PoT and CoT encompassing (1) a new generation paradigm that uses full CoT reasoning to control code generation. (2) Focus Attention that directs model attention to the CoT reasoning during PoT to generate more logical code. (3) reinforcement learning that utilizes the accuracy of both CoT and PoT responses as rewards to prevent repetitive reasoning steps in LLMs when solving difficult math problems. Our method achieves an average improvement of 6.537; on the Llama-Base model and 4.337; on the Mistral-Base model across 8 mathematical calculation datasets. It also shows significant effectiveness on five out-of-domain datasets by controlling the models information flow exhibiting strong transferability. Additionally HTL shows the most significant improvement in non-mathematical natural language inference task contributing to a unified reasoning task framework
