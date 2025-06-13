---
layout: publication
title: 'BRIDGES: Bridging Graph Modality And Large Language Models Within EDA Tasks'
authors: Wei Li, Yang Zou, Christopher Ellis, Ruben Purdy, Shawn Blanton, José M. F. Moura
conference: "Arxiv"
year: 2025
bibkey: li2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05180"}
tags: ['Training Techniques', 'Multimodal Models', 'Prompting', 'Tools']
---
While many EDA tasks already involve graph-based data, existing LLMs in EDA
primarily either represent graphs as sequential text, or simply ignore
graph-structured data that might be beneficial like dataflow graphs of RTL
code. Recent studies have found that LLM performance suffers when graphs are
represented as sequential text, and using additional graph information
significantly boosts performance. To address these challenges, we introduce
BRIDGES, a framework designed to incorporate graph modality into LLMs for EDA
tasks. BRIDGES integrates an automated data generation workflow, a solution
that combines graph modality with LLM, and a comprehensive evaluation suite.
First, we establish an LLM-driven workflow to generate RTL and netlist-level
data, converting them into dataflow and netlist graphs with function
descriptions. This workflow yields a large-scale dataset comprising over
500,000 graph instances and more than 1.5 billion tokens. Second, we propose a
lightweight cross-modal projector that encodes graph representations into
text-compatible prompts, enabling LLMs to effectively utilize graph data
without architectural modifications. Experimental results demonstrate 2x to 10x
improvements across multiple tasks compared to text-only baselines, including
accuracy in design retrieval, type prediction and perplexity in function
description, with negligible computational overhead (<1% model weights increase
and <30% additional runtime overhead). Even without additional LLM finetuning,
our results outperform text-only by a large margin. We plan to release BRIDGES,
including the dataset, models, and training flow.
