---
layout: publication
title: 'Beyond The Last Answer: Your Reasoning Trace Uncovers More Than You Think'
authors: Hasan Abed Al Kader Hammoud, Hani Itani, Bernard Ghanem
conference: "Arxiv"
year: 2025
bibkey: hammoud2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20708"}
  - {name: "Code", url: "https://github.com/hammoudhasan/SubthoughtReasoner"}
tags: ['Prompting', 'RAG', 'Has Code']
---
Large Language Models (LLMs) leverage step-by-step reasoning to solve complex
problems. Standard evaluation practice involves generating a complete reasoning
trace and assessing the correctness of the final answer presented at its
conclusion. In this paper, we challenge the reliance on the final answer by
posing the following two questions: Does the final answer reliably represent
the model's optimal conclusion? Can alternative reasoning paths yield different
results? To answer these questions, we analyze intermediate reasoning steps,
termed subthoughts, and propose a method based on our findings. Our approach
involves segmenting a reasoning trace into sequential subthoughts based on
linguistic cues. We start by prompting the model to generate continuations from
the end-point of each intermediate subthought. We extract a potential answer
from every completed continuation originating from different subthoughts. We
find that aggregating these answers by selecting the most frequent one (the
mode) often yields significantly higher accuracy compared to relying solely on
the answer derived from the original complete trace. Analyzing the consistency
among the answers derived from different subthoughts reveals characteristics
that correlate with the model's confidence and correctness, suggesting
potential for identifying less reliable answers. Our experiments across various
LLMs and challenging mathematical reasoning datasets (AIME2024 and AIME2025)
show consistent accuracy improvements, with gains reaching up to 13% and 10%
respectively. Implementation is available at:
https://github.com/hammoudhasan/SubthoughtReasoner.
