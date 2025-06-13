---
layout: publication
title: 'Finmem: A Performance-enhanced LLM Trading Agent With Layered Memory And Character Design'
authors: Yangyang Yu, Haohang Li, Zhi Chen, Yuechen Jiang, Yang Li, Denghui Zhang, Rong Liu, Jordan W. Suchow, Khaldoun Khashanah
conference: "Arxiv"
year: 2023
bibkey: yu2023performance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13743"}
tags: ['Agentic', 'Agent', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Interpretability and Explainability']
---
Recent advancements in Large Language Models (LLMs) have exhibited notable
efficacy in question-answering (QA) tasks across diverse domains. Their prowess
in integrating extensive web knowledge has fueled interest in developing
LLM-based autonomous agents. While LLMs are efficient in decoding human
instructions and deriving solutions by holistically processing historical
inputs, transitioning to purpose-driven agents requires a supplementary
rational architecture to process multi-source information, establish reasoning
chains, and prioritize critical tasks. Addressing this, we introduce
\textsc\{FinMem\}, a novel LLM-based agent framework devised for financial
decision-making. It encompasses three core modules: Profiling, to customize the
agent's characteristics; Memory, with layered message processing, to aid the
agent in assimilating hierarchical financial data; and Decision-making, to
convert insights gained from memories into investment decisions. Notably,
\textsc\{FinMem\}'s memory module aligns closely with the cognitive structure of
human traders, offering robust interpretability and real-time tuning. Its
adjustable cognitive span allows for the retention of critical information
beyond human perceptual limits, thereby enhancing trading outcomes. This
framework enables the agent to self-evolve its professional knowledge, react
agilely to new investment cues, and continuously refine trading decisions in
the volatile financial environment. We first compare \textsc\{FinMem\} with
various algorithmic agents on a scalable real-world financial dataset,
underscoring its leading trading performance in stocks. We then fine-tuned the
agent's perceptual span and character setting to achieve a significantly
enhanced trading performance. Collectively, \textsc\{FinMem\} presents a
cutting-edge LLM agent framework for automated trading, boosting cumulative
investment returns.
