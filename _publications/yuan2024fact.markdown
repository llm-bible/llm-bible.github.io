---
layout: publication
title: 'Fact-level Confidence Calibration And Self-correction'
authors: Yige Yuan, Bingbing Xu, Hexiang Tan, Fei Sun, Teng Xiao, Wei Li, Huawei Shen, Xueqi Cheng
conference: "Arxiv"
year: 2024
bibkey: yuan2024fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13343"}
tags: ['Tools', 'Reinforcement Learning']
---
Confidence calibration in LLMs, i.e., aligning their self-assessed confidence
with the actual accuracy of their responses, enabling them to self-evaluate the
correctness of their outputs. However, current calibration methods for LLMs
typically estimate two scalars to represent overall response confidence and
correctness, which is inadequate for long-form generation where the response
includes multiple atomic facts and may be partially confident and correct.
These methods also overlook the relevance of each fact to the query. To address
these challenges, we propose a Fact-Level Calibration framework that operates
at a finer granularity, calibrating confidence to relevance-weighted
correctness at the fact level. Furthermore, comprehensive analysis under the
framework inspired the development of Confidence-Guided Fact-level
Self-Correction (\\(\textbf\{ConFix\}\\)), which uses high-confidence facts within a
response as additional knowledge to improve low-confidence ones. Extensive
experiments across four datasets and six models demonstrate that ConFix
effectively mitigates hallucinations without requiring external knowledge
sources such as retrieval systems.
