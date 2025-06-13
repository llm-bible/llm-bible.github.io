---
layout: publication
title: 'CASTILLO: Characterizing Response Length Distributions Of Large Language Models'
authors: Daniel F. Perez-ramirez, Dejan Kostic, Magnus Boman
conference: "Arxiv"
year: 2025
bibkey: perezramirez2025characterizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16881'}
tags: ['Language Modeling', 'GPT', 'Applications', 'Tools', 'Prompting', 'Ethics and Bias', 'Pretraining Methods']
---
Efficiently managing compute resources for Large Language Model (LLM) inference remains challenging due to the inherently stochastic and variable lengths of autoregressive text generation. Accurately estimating response lengths in advance enables proactive resource allocation, yet existing approaches either bias text generation towards certain lengths or rely on assumptions that ignore model- and prompt-specific variability. We introduce CASTILLO, a dataset characterizing response length distributions across 13 widely-used open-source LLMs evaluated on seven distinct instruction-following corpora. For each \\(\langle\\)prompt, model\\(\rangle\\) sample pair, we generate 10 independent completions using fixed decoding hyper-parameters, record the token length of each response, and publish summary statistics (mean, std-dev, percentiles), along with the shortest and longest completions, and the exact generation settings. Our analysis reveals significant inter- and intra-model variability in response lengths (even under identical generation settings), as well as model-specific behaviors and occurrences of partial text degeneration in only subsets of responses. CASTILLO enables the development of predictive models for proactive scheduling and provides a systematic framework for analyzing model-specific generation behaviors. We publicly release the dataset and code to foster research at the intersection of generative language modeling and systems.
