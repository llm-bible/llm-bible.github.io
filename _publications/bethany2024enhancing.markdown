---
layout: publication
title: Enhancing Event Reasoning In Large Language Models Through Instruction Fine45;tuning With Semantic Causal Graphs
authors: Bethany Mazal, Bethany Emet, Wherry Brandon, Chiang Cho-yu, Vishwamitra Nishant, Rios Anthony, Najafirad Peyman
conference: "Arxiv"
year: 2024
bibkey: bethany2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00209"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Survey Paper', 'Training Techniques']
---
Event detection and text reasoning have become critical applications across various domains. While LLMs have recently demonstrated impressive progress in reasoning abilities they often struggle with event detection particularly due to the absence of training methods that consider causal relationships between event triggers and types. To address this challenge we propose a novel approach for instruction fine45;tuning LLMs for event detection. Our method introduces Semantic Causal Graphs (SCGs) to capture both causal relationships and contextual information within text. Building off of SCGs we propose SCG Instructions for fine45;tuning LLMs by focusing on event triggers and their relationships to event types and employ Low45;Rank Adaptation (LoRA) to help preserve the general reasoning abilities of LLMs. Our evaluations demonstrate that training LLMs with SCG Instructions outperforms standard instruction fine45;tuning by an average of 35.6937; on Event Trigger Classification. Notably our fine45;tuned Mistral 7B model also outperforms GPT45;4 on key event detection metrics by an average of 31.0137; on Event Trigger Identification 37.4037; on Event Trigger Classification and 16.4337; on Event Classification. We analyze the retention of general capabilities observing only a minimal average drop of 2.03 points across six benchmarks. This comprehensive study investigates multiple LLMs for the event detection task across various datasets prompting strategies and training approaches.
