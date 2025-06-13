---
layout: publication
title: 'MCTS-KBQA: Monte Carlo Tree Search For Knowledge Base Question Answering'
authors: Guanming Xiong, Haochen Li, Wen Zhao
conference: "Arxiv"
year: 2025
bibkey: xiong2025mcts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13428"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
This study explores how to enhance the reasoning capabilities of large
language models (LLMs) in knowledge base question answering (KBQA) by
leveraging Monte Carlo Tree Search (MCTS). Semantic parsing-based KBQA methods
are particularly challenging as these approaches require locating elements from
knowledge bases and generating logical forms, demanding not only extensive
annotated data but also strong reasoning capabilities. Although recent
approaches leveraging LLMs as agents have demonstrated considerable potential,
these studies are inherently constrained by their linear decision-making
processes. To address this limitation, we propose a MCTS-based framework that
enhances LLMs' reasoning capabilities through tree search methodology. We
design a carefully designed step-wise reward mechanism that requires only
direct prompting of open-source instruction LLMs without additional
fine-tuning. Experimental results demonstrate that our approach significantly
outperforms linear decision-making methods, particularly in low-resource
scenarios. Additionally, we contribute new data resources to the KBQA community
by annotating intermediate reasoning processes for existing question-SPARQL
datasets using distant supervision. Experimental results on the extended
dataset demonstrate that our method achieves comparable performance to fully
supervised models while using significantly less training data.
