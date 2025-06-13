---
layout: publication
title: 'Iteration Of Thought: Leveraging Inner Dialogue For Autonomous Large Language Model Reasoning'
authors: Santosh Kumar Radha, Yasamin Nouri Jelyani, Ara Ghukasyan, Oktay Goktas
conference: "Arxiv"
year: 2024
bibkey: radha2024iteration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12618"}
tags: ['Agentic', 'Tools', 'RAG', 'Fine-Tuning', 'Prompting', 'Applications']
---
Iterative human engagement is a common and effective means of leveraging the
advanced language processing power of large language models (LLMs). Using
well-structured prompts in a conversational manner, human users can effectively
influence an LLM to develop more thoughtful and accurate responses. Motivated
by this insight, we propose the Iteration of Thought (IoT) framework for
enhancing LLM responses by generating "thought"-provoking prompts vis a vis an
input query and the current iteration of an LLM's response. Unlike static or
semi-static approaches, e.g. Chain of Thought (CoT) or Tree of Thoughts (ToT),
IoT adapts its reasoning path dynamically, based on evolving context, and
without generating alternate explorative thoughts which are ultimately
discarded. The three components of the IoT framework are (1) an Inner Dialogue
Agent (IDA) responsible for generating instructive, context-specific prompts;
(2) an LLM Agent (LLMA) that processes these prompts to refine its responses;
and (3) an iterative prompting loop that implements a conversation between the
former two components. We introduce two variants of our framework: Autonomous
Iteration of Thought (AIoT), where an LLM decides when to stop iterating, and
Guided Iteration of Thought (GIoT), which always forces a fixed number
iterations. We investigate the performance of IoT across various datasets,
spanning complex reasoning tasks from the GPQA dataset, explorative
problem-solving in Game of 24, puzzle solving in Mini Crosswords, and multi-hop
question answering from the HotpotQA dataset. Our results show that IoT
represents a viable paradigm for autonomous response refinement in LLMs,
showcasing significant improvements over CoT and thereby enabling more adaptive
and efficient reasoning systems that minimize human intervention.
