---
layout: publication
title: 'SG-FSM: A Self-guiding Zero-shot Prompting Paradigm For Multi-hop Question Answering Based On Finite State Machine'
authors: Xiaochen Wang, Junqing He, Liang Chen, Reza Haf Zhe Yang, Yiru Wang, Xiangdi Meng, Kunhao Pan, Zhifang Sui
conference: "Arxiv"
year: 2024
bibkey: wang2024sg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17021"}
tags: ['Prompting', 'Applications']
---
Large Language Models with chain-of-thought prompting, such as OpenAI-o1,
have shown impressive capabilities in natural language inference tasks.
However, Multi-hop Question Answering (MHQA) remains challenging for many
existing models due to issues like hallucination, error propagation, and
limited context length. To address these challenges and enhance LLMs'
performance on MHQA, we propose the Self-Guiding prompting Finite State Machine
(SG-FSM), designed to strengthen multi-hop reasoning abilities. Unlike
traditional chain-of-thought methods, SG-FSM tackles MHQA by iteratively
breaking down complex questions into sub-questions, correcting itself to
improve accuracy. It processes one sub-question at a time, dynamically deciding
the next step based on the current context and results, functioning much like
an automaton. Experiments across various benchmarks demonstrate the
effectiveness of our approach, outperforming strong baselines on challenging
datasets such as Musique. SG-FSM reduces hallucination, enabling recovery of
the correct final answer despite intermediate errors. It also improves
adherence to specified output formats, simplifying evaluation significantly.
