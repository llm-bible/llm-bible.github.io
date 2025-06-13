---
layout: publication
title: 'TALE: A Tool-augmented Framework For Reference-free Evaluation Of Large Language Models'
authors: Sher Badshah, Ali Emami, Hassan Sajjad
conference: "Arxiv"
year: 2025
bibkey: badshah2025tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07385"}
tags: ['Agentic', 'Reinforcement Learning', 'Applications', 'Tools']
---
As Large Language Models (LLMs) become increasingly integrated into
real-world, autonomous applications, relying on static, pre-annotated
references for evaluation poses significant challenges in cost, scalability,
and completeness. We propose Tool-Augmented LLM Evaluation (TALE), a framework
to assess LLM outputs without predetermined ground-truth answers. Unlike
conventional metrics that compare to fixed references or depend solely on
LLM-as-a-judge knowledge, TALE employs an agent with tool-access capabilities
that actively retrieves and synthesizes external evidence. It iteratively
generates web queries, collects information, summarizes findings, and refines
subsequent searches through reflection. By shifting away from static
references, TALE aligns with free-form question-answering tasks common in
real-world scenarios. Experimental results on multiple free-form QA benchmarks
show that TALE not only outperforms standard reference-based metrics for
measuring response accuracy but also achieves substantial to near-perfect
agreement with human evaluations. TALE enhances the reliability of LLM
evaluations in real-world, dynamic scenarios without relying on static
references.
