---
layout: publication
title: 'Truth Or Deceit? A Bayesian Decoding Game Enhances Consistency And Reliability'
authors: Weitong Zhang, Chengqi Zang, Bernhard Kainz
conference: "Arxiv"
year: 2024
bibkey: zhang2024truth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01064"}
tags: ['Tools', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) often produce outputs that -- though plausible
-- can lack consistency and reliability, particularly in ambiguous or complex
scenarios. Challenges arise from ensuring that outputs align with both factual
correctness and human intent. This is problematic in existing approaches that
trade improved consistency for lower accuracy. To mitigate these challenges, we
propose a novel game-theoretic approach to enhance consistency and reliability
during the decoding stage of LLM output generation. Our method models the
decoding process as a multistage Bayesian decoding game. This ensures
consistency through Correctness Alignment and enhances reliability via
Ambiguity Calibration. The model dynamically converges to a consensus on the
most reliable outputs and distinguishes \{Valid, Specious\} outputs without human
feedback or additional training. Our game design allows smaller models to
outperform much larger models through game mechanisms (e.g., 78.1 LLaMA13B vs
76.6 PaLM540B), as well as integrating various LL strategies and models,
demonstrating the potential of game-theoretic tools to improve the truthfulness
and reliability of LLMs.
