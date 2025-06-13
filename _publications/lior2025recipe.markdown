---
layout: publication
title: 'Reliableeval: A Recipe For Stochastic LLM Evaluation Via Method Of Moments'
authors: Gili Lior, Eliya Habba, Shahar Levy, Avi Caciularu, Gabriel Stanovsky
conference: "Arxiv"
year: 2025
bibkey: lior2025recipe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22169"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Tools']
---
LLMs are highly sensitive to prompt phrasing, yet standard benchmarks typically report performance using a single prompt, raising concerns about the reliability of such evaluations. In this work, we argue for a stochastic method of moments evaluation over the space of meaning-preserving prompt perturbations. We introduce a formal definition of reliable evaluation that accounts for prompt sensitivity, and suggest ReliableEval - a method for estimating the number of prompt resamplings needed to obtain meaningful results. Using our framework, we stochastically evaluate five frontier LLMs and find that even top-performing models like GPT-4o and Claude-3.7-Sonnet exhibit substantial prompt sensitivity. Our approach is model-, task-, and metric-agnostic, offering a recipe for meaningful and robust LLM evaluation.
