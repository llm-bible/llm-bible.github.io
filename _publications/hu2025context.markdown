---
layout: publication
title: 'Context-alignment: Activating And Enhancing LLM Capabilities In Time Series'
authors: Yuxiao Hu, Qian Li, Dongxiao Zhang, Jinyue Yan, Yuntian Chen
conference: "Arxiv"
year: 2025
bibkey: hu2025context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03747"}
tags: ['Multimodal Models', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Attention Mechanism']
---
Recently, leveraging pre-trained Large Language Models (LLMs) for time series
(TS) tasks has gained increasing attention, which involves activating and
enhancing LLMs' capabilities. Many methods aim to activate LLMs' capabilities
based on token-level alignment but overlook LLMs' inherent strength on natural
language processing -- their deep understanding of linguistic logic and
structure rather than superficial embedding processing. We propose
Context-Alignment, a new paradigm that aligns TS with a linguistic component in
the language environments familiar to LLMs to enable LLMs to contextualize and
comprehend TS data, thereby activating their capabilities. Specifically, such
context-level alignment comprises structural alignment and logical alignment,
which is achieved by a Dual-Scale Context-Alignment GNNs (DSCA-GNNs) applied to
TS-language multimodal inputs. Structural alignment utilizes dual-scale nodes
to describe hierarchical structure in TS-language, enabling LLMs treat long TS
data as a whole linguistic component while preserving intrinsic token features.
Logical alignment uses directed edges to guide logical relationships, ensuring
coherence in the contextual semantics. Demonstration examples prompt are
employed to construct Demonstration Examples based Context-Alignment (DECA)
following DSCA-GNNs framework. DECA can be flexibly and repeatedly integrated
into various layers of pre-trained LLMs to improve awareness of logic and
structure, thereby enhancing performance. Extensive experiments show the
effectiveness of DECA and the importance of Context-Alignment across tasks,
particularly in few-shot and zero-shot forecasting, confirming that
Context-Alignment provide powerful prior knowledge on context.
