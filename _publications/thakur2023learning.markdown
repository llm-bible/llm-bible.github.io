---
layout: publication
title: 'An In-context Learning Agent For Formal Theorem-proving'
authors: Amitayush Thakur, George Tsoukalas, Yeming Wen, Jimmy Xin, Swarat Chaudhuri
conference: "Arxiv"
year: 2023
bibkey: thakur2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04353"}
  - {name: "Code", url: "https://github.com/trishullab/copra"}
tags: ['Agentic', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'GPT', 'Has Code', 'Prompting', 'Applications', 'In-Context Learning']
---
We present an in-context learning agent for formal theorem-proving in
environments like Lean and Coq. Current state-of-the-art models for the problem
are finetuned on environment-specific proof data. By contrast, our approach,
called COPRA, repeatedly asks a high-capacity, general-purpose large language
model (GPT-4) to propose tactic applications from within a stateful
backtracking search. Proposed tactics are executed in the underlying proof
environment. Feedback from the execution is used to build the prompt for the
next model query, along with selected information from the search history and
lemmas retrieved from an external database. We evaluate our implementation of
COPRA on the miniF2F benchmark for Lean and a set of Coq tasks from the
CompCert project. On these benchmarks, COPRA significantly outperforms few-shot
invocations of GPT-4. It also compares favorably against finetuning-based
approaches, outperforming ReProver, a state-of-the-art finetuned approach for
Lean, in terms of the pass@1 metric. Our code and data are available at
https://github.com/trishullab/copra.
