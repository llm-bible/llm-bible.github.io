---
layout: publication
title: Fine-tuning, Quantization, And Llms: Navigating Unintended Outcomes
authors: Kumar Divyanshu, Kumar Anurakt, Agarwal Sahil, Harshangi Prashanth
conference: "Arxiv"
year: 2024
bibkey: kumar2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04392"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Quantization', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) have gained widespread adoption across various domains including chatbots and auto-task completion agents. However these models are susceptible to safety vulnerabilities such as jailbreaking prompt injection and privacy leakage attacks. These vulnerabilities can lead to the generation of malicious content unauthorized actions or the disclosure of confidential information. While foundational LLMs undergo alignment training and incorporate safety measures they are often subject to fine-tuning or doing quantization resource-constrained environments. This study investigates the impact of these modifications on LLM safety a critical consideration for building reliable and secure AI systems. We evaluate foundational models including Mistral Llama series Qwen and MosaicML along with their fine-tuned variants. Our comprehensive analysis reveals that fine-tuning generally increases the success rates of jailbreak attacks while quantization has variable effects on attack success rates. Importantly we find that properly implemented guardrails significantly enhance resistance to jailbreak attempts. These findings contribute to our understanding of LLM vulnerabilities and provide insights for developing more robust safety strategies in the deployment of language models.
