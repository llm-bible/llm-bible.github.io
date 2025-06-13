---
layout: publication
title: 'Multi-agent Conversational Online Learning For Adaptive LLM Response Identification'
authors: Xiangxiang Dai, Yuejin Xie, Maoli Liu, Xuchuang Wang, Zhuohua Li, Huanyu Wang, John C. S. Lui
conference: "Arxiv"
year: 2025
bibkey: dai2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01849"}
tags: ['RAG', 'Agentic', 'Applications', 'Reinforcement Learning']
---
The remarkable generative capability of large language models (LLMs) has
sparked a growing interest in automatically generating responses for different
applications. Given the dynamic nature of user preferences and the uncertainty
of LLM response performance, it is crucial to design efficient online learning
algorithms to identify optimal LLM responses (i.e., high-quality responses that
also meet user preferences). Most existing online algorithms adopt a
centralized approach and fail to leverage explicit user preferences for more
efficient and personalized LLM response identification. In contrast, this paper
introduces \textit\{MACO\} (\underline\{M\}ulti-\underline\{A\}gent
\underline\{C\}onversational \underline\{O\}nline Learning for Adaptive LLM
Response Identification): 1) The online LLM response identification process is
accelerated by multiple local agents (such as smartphones), while enhancing
data privacy; 2) A novel conversational mechanism is proposed to adaptively
conduct conversations for soliciting user preferences (e.g., a preference for a
humorous tone over a serious one in generated responses), so to minimize
uncertainty in preference estimation. Our theoretical analysis demonstrates
that \cadi\ is near-optimal regarding cumulative regret. Additionally, \cadi\
offers reduced communication costs and computational complexity by eliminating
the traditional, computing-intensive ``G-optimal design" found in previous
works. Extensive experiments with the open LLM \textit\{Llama\}, coupled with two
different embedding models from Google and OpenAI for text vector
representation, demonstrate that \cadi\ significantly outperforms the current
state-of-the-art in online LLM response identification.
