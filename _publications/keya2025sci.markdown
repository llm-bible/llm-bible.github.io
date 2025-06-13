---
layout: publication
title: 'SCI-IDEA: Context-aware Scientific Ideation Using Token And Sentence Embeddings'
authors: Farhana Keya, Gollam Rabby, Prasenjit Mitra, Sahar Vahdati, Sören Auer, Yaser Jaradeh
conference: "Arxiv"
year: 2025
bibkey: keya2025sci
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19257"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Prompting']
---
Every scientific discovery starts with an idea inspired by prior work,
interdisciplinary concepts, and emerging challenges. Recent advancements in
large language models (LLMs) trained on scientific corpora have driven interest
in AI-supported idea generation. However, generating context-aware,
high-quality, and innovative ideas remains challenging. We introduce SCI-IDEA,
a framework that uses LLM prompting strategies and Aha Moment detection for
iterative idea refinement. SCI-IDEA extracts essential facets from research
publications, assessing generated ideas on novelty, excitement, feasibility,
and effectiveness. Comprehensive experiments validate SCI-IDEA's effectiveness,
achieving average scores of 6.84, 6.86, 6.89, and 6.84 (on a 1-10 scale) across
novelty, excitement, feasibility, and effectiveness, respectively. Evaluations
employed GPT-4o, GPT-4.5, DeepSeek-32B (each under 2-shot prompting), and
DeepSeek-70B (3-shot prompting), with token-level embeddings used for Aha
Moment detection. Similarly, it achieves scores of 6.87, 6.86, 6.83, and 6.87
using GPT-4o under 5-shot prompting, GPT-4.5 under 3-shot prompting,
DeepSeek-32B under zero-shot chain-of-thought prompting, and DeepSeek-70B under
5-shot prompting with sentence-level embeddings. We also address ethical
considerations such as intellectual credit, potential misuse, and balancing
human creativity with AI-driven ideation. Our results highlight SCI-IDEA's
potential to facilitate the structured and flexible exploration of
context-aware scientific ideas, supporting innovation while maintaining ethical
standards.
