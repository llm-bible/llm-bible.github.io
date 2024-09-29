---
layout: publication
title: AMOR A Recipe For Building Adaptable Modular Knowledge Agents Through Process Feedback
authors: Guan Jian, Wu Wei, Wen Zujie, Xu Peng, Wang Hongning, Huang Minlie
conference: "Arxiv"
year: 2024
bibkey: guan2024recipe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01469"}
tags: ['Agentic', 'Pretraining Methods', 'Tools']
---
The notable success of large language models (LLMs) has sparked an upsurge in building language agents to complete various complex tasks. We present AMOR an agent framework based on open45;source LLMs which reasons with external knowledge bases and adapts to specific domains through human supervision to the reasoning process. AMOR builds reasoning logic over a finite state machine (FSM) that solves problems through autonomous executions and transitions over disentangled modules. This allows humans to provide direct feedback to the individual modules and thus naturally forms process supervision. Based on this reasoning and feedback framework we develop AMOR through two45;stage fine45;tuning warm45;up and adaptation. The former fine45;tunes the LLM with examples automatically constructed from various public datasets and enables AMOR to generalize across different knowledge environments while the latter tailors AMOR to specific domains using process feedback. Extensive experiments across multiple domains demonstrate the advantage of AMOR to strong baselines thanks to its FSM45;based reasoning and process feedback mechanism.
