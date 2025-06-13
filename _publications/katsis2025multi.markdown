---
layout: publication
title: 'MTRAG: A Multi-turn Conversational Benchmark For Evaluating Retrieval-augmented Generation Systems'
authors: Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky
conference: "Arxiv"
year: 2025
bibkey: katsis2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03468"}
  - {name: "Code", url: "https://github.com/ibm/mt-rag-benchmark"}
tags: ['RAG', 'Has Code', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) has recently become a very popular task
for Large Language Models (LLMs). Evaluating them on multi-turn RAG
conversations, where the system is asked to generate a response to a question
in the context of a preceding conversation is an important and often overlooked
task with several additional challenges. We present MTRAG: an end-to-end
human-generated multi-turn RAG benchmark that reflects several real-world
properties across diverse dimensions for evaluating the full RAG pipeline.
MTRAG contains 110 conversations averaging 7.7 turns each across four domains
for a total of 842 tasks. We also explore automation paths via synthetic data
and LLM-as-a-Judge evaluation. Our human and automatic evaluations show that
even state-of-the-art LLM RAG systems struggle on MTRAG. We demonstrate the
need for strong retrieval and generation systems that can handle later turns,
unanswerable questions, non-standalone questions, and multiple domains. MTRAG
is available at https://github.com/ibm/mt-rag-benchmark.
