---
layout: publication
title: 'MEDAL: A Framework For Benchmarking Llms As Multilingual Open-domain Chatbots And Dialogue Evaluators'
authors: John Mendonça, Alon Lavie, Isabel Trancoso
conference: "Arxiv"
year: 2025
bibkey: mendonça2025framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22777"}
tags: ['Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning']
---
As the capabilities of chatbots and their underlying LLMs continue to dramatically improve, evaluating their performance has increasingly become a major blocker to their further development. A major challenge is the available benchmarking datasets, which are largely static, outdated, and lacking in multilingual coverage, limiting their ability to capture subtle linguistic and cultural variations. This paper introduces MEDAL, an automated multi-agent framework for generating, evaluating, and curating more representative and diverse open-domain dialogue evaluation benchmarks. Our approach leverages several state-of-the-art LLMs to generate user-chatbot multilingual dialogues, conditioned on varied seed contexts. A strong LLM (GPT-4.1) is then used for a multidimensional analysis of the performance of the chatbots, uncovering noticeable cross-lingual performance differences. Guided by this large-scale evaluation, we curate a new meta-evaluation multilingual benchmark and human-annotate samples with nuanced quality judgments. This benchmark is then used to assess the ability of several reasoning and non-reasoning LLMs to act as evaluators of open-domain dialogues. We find that current LLMs struggle to detect nuanced issues, particularly those involving empathy and reasoning.
