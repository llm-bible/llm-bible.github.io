---
layout: publication
title: 'Are Large Language Models Strategic Decision Makers? A Study Of Performance And Bias In Two-player Non-zero-sum Games'
authors: Nathan Herr, Fernando Acero, Roberta Raileanu, María Pérez-ortiz, Zhibin Li
conference: "Arxiv"
year: 2024
bibkey: herr2024are
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.04467'}
tags: ['RAG', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
Large Language Models (LLMs) have been increasingly used in real-world
settings, yet their strategic decision-making abilities remain largely
unexplored. To fully benefit from the potential of LLMs, it's essential to
understand their ability to function in complex social scenarios. Game theory,
which is already used to understand real-world interactions, provides a good
framework for assessing these abilities. This work investigates the performance
and merits of LLMs in canonical game-theoretic two-player non-zero-sum games,
Stag Hunt and Prisoner Dilemma. Our structured evaluation of GPT-3.5,
GPT-4-Turbo, GPT-4o, and Llama-3-8B shows that these models, when making
decisions in these games, are affected by at least one of the following
systematic biases: positional bias, payoff bias, or behavioural bias. This
indicates that LLMs do not fully rely on logical reasoning when making these
strategic decisions. As a result, it was found that the LLMs' performance drops
when the game configuration is misaligned with the affecting biases. When
misaligned, GPT-3.5, GPT-4-Turbo, GPT-4o, and Llama-3-8B show an average
performance drop of 32%, 25%, 34%, and 29% respectively in Stag Hunt, and
28%, 16%, 34%, and 24% respectively in Prisoner's Dilemma. Surprisingly,
GPT-4o (a top-performing LLM across standard benchmarks) suffers the most
substantial performance drop, suggesting that newer models are not addressing
these issues. Interestingly, we found that a commonly used method of improving
the reasoning capabilities of LLMs, chain-of-thought (CoT) prompting, reduces
the biases in GPT-3.5, GPT-4o, and Llama-3-8B but increases the effect of the
bias in GPT-4-Turbo, indicating that CoT alone cannot fully serve as a robust
solution to this problem. We perform several additional experiments, which
provide further insight into these observed behaviours.
