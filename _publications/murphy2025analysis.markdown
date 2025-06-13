---
layout: publication
title: 'An Analysis Of Decoding Methods For Llm-based Agents For Faithful Multi-hop Question Answering'
authors: Alexander Murphy, Mohd Sanad Zaki Rizvi, Aden Haussmann, Ping Nie, Guifu Liu, Aryo Pradipta Gema, Pasquale Minervini
conference: "Arxiv"
year: 2025
bibkey: murphy2025analysis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23415"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'RAG', 'Applications']
---
Large Language Models (LLMs) frequently produce factually inaccurate outputs
- a phenomenon known as hallucination - which limits their accuracy in
knowledge-intensive NLP tasks. Retrieval-augmented generation and agentic
frameworks such as Reasoning and Acting (ReAct) can address this issue by
giving the model access to external knowledge. However, LLMs often fail to
remain faithful to retrieved information. Mitigating this is critical,
especially if LLMs are required to reason about the retrieved information.
Recent research has explored training-free decoding strategies to improve the
faithfulness of model generations. We present a systematic analysis of how the
combination of the ReAct framework and decoding strategies (i.e., DeCoRe, DoLa,
and CAD) can influence the faithfulness of LLM-generated answers. Our results
show that combining an agentic framework for knowledge retrieval with decoding
methods that enhance faithfulness can increase accuracy on the downstream
Multi-Hop Question Answering tasks. For example, we observe an F1 increase from
19.5 to 32.6 on HotpotQA when using ReAct and DoLa.
