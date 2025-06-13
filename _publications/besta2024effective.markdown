---
layout: publication
title: 'Checkembed: Effective Verification Of LLM Solutions To Open-ended Tasks'
authors: Maciej Besta, Lorenzo Paleari, Marcin Copik, Robert Gerstenberger, Ales Kubicek, Piotr Nyczyk, Patrick Iff, Eric Schreiber, Tanja Srindran, Tomasz Lehmann, Hubert Niewiadomski, Torsten Hoefler
conference: "Arxiv"
year: 2024
bibkey: besta2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02524"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'BERT', 'Applications']
---
Large Language Models (LLMs) are transforming a wide range of domains, yet verifying their outputs remains a significant challenge, especially for complex open-ended tasks such as consolidation, summarization, and knowledge extraction. To address this, we introduce CheckEmbed (CE): a simple, scalable, and accurate verification method. CE reduces each LLM answer to a single embedding vector using powerful modern embedding LLM models like SFR-Embedding-Mistral. Prior methods such as BERTScore and SelfCheckGPT relied on weaker encoders like BERT, forcing them to operate at token or sentence granularity. In contrast, CE performs fast, semantically rich comparisons directly at the whole-answer level, overcoming key limitations in both accuracy and scalability. We conduct a comprehensive design and time complexity analysis across 13 verification baselines, including classical text scorers (e.g., BLEU), stability-based methods (e.g., SelfCheckGPT), and generative evaluators (e.g., LLM-as-a-Judge), which highlights the effectiveness, efficiency, versatility, and simplicity of CE. Empirical results show that CE reliably detects hallucinations in both closed and open-ended tasks. We further present evidence that CE generalizes beyond text to other modalities such as vision, establishing it as a practical and versatile verification framework.
