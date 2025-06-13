---
layout: publication
title: 'Efficient In-domain Question Answering For Resource-constrained Environments'
authors: Isaac Chung, Phat Vo, Arman C. Kizilkale, Aaron Reite
conference: "Arxiv"
year: 2024
bibkey: chung2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17648"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Fine-Tuning', 'Prompting', 'Applications']
---
Retrieval Augmented Generation (RAG) is a common method for integrating
external knowledge into pretrained Large Language Models (LLMs) to enhance
accuracy and relevancy in question answering (QA) tasks. However, prompt
engineering and resource efficiency remain significant bottlenecks in
developing optimal and robust RAG solutions for real-world QA applications.
Recent studies have shown success in using fine tuning to address these
problems; in particular, Retrieval Augmented Fine Tuning (RAFT) applied to
smaller 7B models has demonstrated superior performance compared to RAG setups
with much larger models such as GPT-3.5. The combination of RAFT with
parameter-efficient fine tuning (PEFT) techniques, such as Low-Rank Adaptation
(LoRA), promises an even more efficient solution, yet remains an unexplored
area. In this work, we combine RAFT with LoRA to reduce fine tuning and storage
requirements and gain faster inference times while maintaining comparable RAG
performance. This results in a more compute-efficient RAFT, or CRAFT, which is
particularly useful for knowledge-intensive QA tasks in resource-constrained
environments where internet access may be restricted and hardware resources
limited.
