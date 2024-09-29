---
layout: publication
title: FSM: A Finite State Machine Based Zero-shot Prompting Paradigm For Multi-hop Question Answering
authors: Wang Xiaochen, He Junqing, Yang Zhe, Wang Yiru, Meng Xiangdi, Pan Kunhao, Sui Zhifang
conference: "Arxiv"
year: 2024
bibkey: wang2024finite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02964"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) with chain-of-thought (COT) prompting have demonstrated impressive abilities on simple nature language inference tasks. However they tend to perform poorly on Multi-hop Question Answering (MHQA) tasks due to several challenges including hallucination error propagation and limited context length. We propose a prompting method Finite State Machine (FSM) to enhance the reasoning capabilities of LLM for complex tasks in addition to improved effectiveness and trustworthiness. Different from COT methods FSM addresses MHQA by iteratively decomposing a question into multi-turn sub-questions and self-correcting in time improving the accuracy of answers in each step. Specifically FSM addresses one sub-question at a time and decides on the next step based on its current result and state in an automaton-like format. Experiments on benchmarks show the effectiveness of our method. Although our method performs on par with the baseline on relatively simpler datasets it excels on challenging datasets like Musique. Moreover this approach mitigates the hallucination phenomenon wherein the correct final answer can be recovered despite errors in intermediate reasoning. Furthermore our method improves LLMs ability to follow specified output format requirements significantly reducing the difficulty of answer interpretation and the need for reformatting.
