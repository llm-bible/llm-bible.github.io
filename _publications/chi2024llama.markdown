---
layout: publication
title: 'Llama Guard 3 Vision: Safeguarding Human-ai Image Understanding Conversations'
authors: Jianfeng Chi, Ujjwal Karn, Hongyuan Zhan, Eric Smith, Javier Rando, Yiming Zhang, Kate Plawiak, Zacharie Delpierre Coudert, Kartikeya Upasani, Mahesh Pasupuleti
conference: "Arxiv"
year: 2024
bibkey: chi2024llama
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10414'}
tags: ['Security', 'Applications', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
We introduce Llama Guard 3 Vision, a multimodal LLM-based safeguard for
human-AI conversations that involves image understanding: it can be used to
safeguard content for both multimodal LLM inputs (prompt classification) and
outputs (response classification). Unlike the previous text-only Llama Guard
versions (Inan et al., 2023; Llama Team, 2024b,a), it is specifically designed
to support image reasoning use cases and is optimized to detect harmful
multimodal (text and image) prompts and text responses to these prompts. Llama
Guard 3 Vision is fine-tuned on Llama 3.2-Vision and demonstrates strong
performance on the internal benchmarks using the MLCommons taxonomy. We also
test its robustness against adversarial attacks. We believe that Llama Guard 3
Vision serves as a good starting point to build more capable and robust content
moderation tools for human-AI conversation with multimodal capabilities.
