---
layout: publication
title: Evaluating LLMs Inherent Multi-hop Reasoning Ability
authors: Wu Jian, Yang Linyi, Wang Zhen, Okumura Manabu, Zhang Yue
conference: "Arxiv"
year: 2024
bibkey: wu2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11924"}
tags: ['ARXIV', 'LLM', 'PRE Training', 'Training Techniques']
---
While Large Language Models (LLMs) excel in question-answering (QA) tasks their multi-step reasoning abilities on multiple evidence integration on Multi-hop QA tasks remain underexplored. LLMs sometimes generate answers that rely on internal memory rather than reasoning given context which brings concerns about the evaluation quality of real reasoning abilities. The counterfactual QA task can separate internal memory from reasoning abilities but focusing solely on final-QA performance without evaluating the multi-step reasoning process is insufficient for reporting LLMs real reasoning abilities. Current Multi-hop QA (MHQA) benchmarks are factual and annotated on open-source corpora such as Wikipedia although useful for multi-step reasoning evaluation showing limitations due to potential data contamination in LLMs pre-training stage. To address this issue we introduce the Inherent Reasoning Evaluation (IRE) method a novel evaluation way that jointly evaluates the LLMs chain-of-reasoning performance based on the first knowledge-edited counterfactual multi-hop QA data which involves editing the original Wikipedia passages reducing data contamination risks. The IRE comprehensively assesses reasoning chains through sub-QA and final-QA evaluations. Our comparisons reveal significant performance gaps for several LLMs between Wikipedia-based benchmarks and IRE deeming data contamination issues in existing benchmarks. We believe that the IRE benchmark will enhance and facilitate trustworthy LLM evaluations.
