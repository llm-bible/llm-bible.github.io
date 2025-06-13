---
layout: publication
title: 'Enhancing Financial Question Answering With A Multi-agent Reflection Framework'
authors: Sorouralsadat Fatemi, Yuheng Hu
conference: "Arxiv"
year: 2024
bibkey: fatemi2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21741'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'GPT', 'Tools', 'Applications', 'Reinforcement Learning']
---
While Large Language Models (LLMs) have shown impressive capabilities in
numerous Natural Language Processing (NLP) tasks, they still struggle with
financial question answering (QA), particularly when numerical reasoning is
required. Recently, LLM-based multi-agent frameworks have demonstrated
remarkable effectiveness in multi-step reasoning, which is crucial for
financial QA tasks as it involves extracting relevant information from tables
and text and then performing numerical reasoning on the extracted data to infer
answers. In this study, we propose a multi-agent framework incorporating a
critic agent that reflects on the reasoning steps and final answers for each
question. Additionally, we enhance our system by adding multiple critic agents,
each focusing on a specific aspect of the answer. Our results indicate that
this framework significantly improves performance compared to single-agent
reasoning, with an average performance increase of 15% for the LLaMA3-8B model
and 5% for the LLaMA3-70B model. Furthermore, our framework performs on par
with, and in some cases surpasses, larger single-agent LLMs such as
LLaMA3.1-405B and GPT-4o-mini, though it falls slightly short compared to
Claude-3.5 Sonnet. Overall, our framework presents an effective solution to
enhance open-source LLMs for financial QA tasks, offering a cost-effective
alternative to larger models like Claude-3.5 Sonnet.
