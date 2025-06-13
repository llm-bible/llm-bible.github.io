---
layout: publication
title: 'Aligning Llms With Human Instructions And Stock Market Feedback In Financial Sentiment Analysis'
authors: Zijie Zhao, Roy E. Welsch
conference: "Arxiv"
year: 2024
bibkey: zhao2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14926"}
tags: ['Tools', 'RAG', 'Agentic', 'Reinforcement Learning']
---
Financial sentiment analysis is crucial for trading and investment
decision-making. This study introduces an adaptive retrieval augmented
framework for Large Language Models (LLMs) that aligns with human instructions
through Instruction Tuning and incorporates market feedback to dynamically
adjust weights across various knowledge sources within the Retrieval-Augmented
Generation (RAG) module. Building upon foundational models like LLaMA 2, we
fine-tune a series of LLMs ranging from 7B to 70B in size, enriched with
Instruction Tuning and RAG, and further optimized through direct feedback and
Reinforcement Learning (RL)-based refinement methods applied to the source
weights of RAG.Through extensive evaluation, we demonstrate that the sentiment
outputs from our LLMs more accurately mirror the intrinsic sentiment of textual
data, showcasing a 1% to 6% boost in accuracy and F1 score over existing
state-of-the-art models and leading conversational AI systems. Moreover, the
sentiments extracted are more indicative of the directions in stock price
movements. On top of that, we successfully construct portfolios that yield a
3.61% higher Sharpe ratio compared to the S&P 500 baseline in bullish markets.
These portfolios also demonstrate resilience in bearish markets, with a 5x
reduction in return losses compared to those typically experienced by the S&P
500.
