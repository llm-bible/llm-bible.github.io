---
layout: publication
title: 'Checkembed: Effective Verification Of LLM Solutions To Open-ended Tasks'
authors: Besta Maciej, Paleari Lorenzo, Kubicek Ales, Nyczyk Piotr, Gerstenberger Robert, Iff Patrick, Lehmann Tomasz, Niewiadomski Hubert, Hoefler Torsten
conference: "Arxiv"
year: 2024
bibkey: besta2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02524"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) are revolutionizing various domains yet verifying their answers remains a significant challenge especially for intricate open-ended tasks such as consolidation summarization and extraction of knowledge. In this work we propose CheckEmbed an accurate scalable and simple LLM verification approach. CheckEmbed is driven by a straightforward yet powerful idea in order to compare LLM solutions to one another or to the ground-truth compare their corresponding answer-level embeddings obtained with a model such as GPT Text Embedding Large. This reduces a complex textual answer to a single embedding facilitating straightforward fast and meaningful verification. We develop a comprehensive verification pipeline implementing the CheckEmbed methodology. The CheckEmbed pipeline also comes with metrics for assessing the truthfulness of the LLM answers such as embedding heatmaps and their summaries. We show how to use these metrics for deploying practical engines that decide whether an LLM answer is satisfactory or not. We apply the pipeline to real-world document analysis tasks including term extraction and document summarization showcasing significant improvements in accuracy cost-effectiveness and runtime performance compared to existing token- sentence- and fact-level schemes such as BERTScore or SelfCheckGPT.
