---
layout: publication
title: 'Guiding Reasoning In Small Language Models With LLM Assistance'
authors: Yujin Kim, Euiin Yi, Minu Kim, Se-young Yun, Taehyeon Kim
conference: "Arxiv"
year: 2025
bibkey: kim2025guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09923"}
tags: ['Tools']
---
The limited reasoning capabilities of small language models (SLMs) cast doubt on their suitability for tasks demanding deep, multi-step logical deduction. This paper introduces a framework called Small Reasons, Large Hints (SMART), which selectively augments SLM reasoning with targeted guidance from large language models (LLMs). Inspired by the concept of cognitive scaffolding, SMART employs a score-based evaluation to identify uncertain reasoning steps and injects corrective LLM-generated reasoning only when necessary. By framing structured reasoning as an optimal policy search, our approach steers the reasoning trajectory toward correct solutions without exhaustive sampling. Our experiments on mathematical reasoning datasets demonstrate that targeted external scaffolding significantly improves performance, paving the way for collaborative use of both SLM and LLM to tackle complex reasoning tasks that are currently unsolvable by SLMs alone.
