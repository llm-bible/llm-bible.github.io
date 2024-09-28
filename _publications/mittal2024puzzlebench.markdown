---
layout: publication
title: PuzzleBench Can LLMs Solve Challenging First-Order Combinatorial Reasoning Problems
authors: Mittal Chinmay, Kartik Krishna, Mausam, Singla Parag
conference: "Arxiv"
year: 2024
bibkey: mittal2024puzzlebench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02611"}
tags: ['ARXIV', 'Pretraining Methods']
---
Recent works show that the largest of the large language models (LLMs) can solve many simple reasoning tasks expressed in natural language without any/much supervision. But can they also solve challenging first-order combinatorial reasoning problems such as graph coloring knapsack and cryptarithmetic To answer this question we present PuzzleBench a dataset of 31 such challenging problems along with a few solved instances for each problem. These problems are all first order i.e. they can be instantiated with problem instances of varying sizes and most of them are NP-hard requiring several reasoning steps to reach the solution. We first observe that LLMs even when aided by symbolic solvers perform rather poorly on our dataset. In response we propose a new approach Puzzle-LM which combines LLMs with both symbolic solvers and program interpreters along with feedback from solved examples to achieve huge performance gains. Our extensive experimentation and analyses offer new insights into the reasoning abilities and limitations of present-day LLMs.
