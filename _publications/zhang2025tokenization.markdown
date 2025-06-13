---
layout: publication
title: 'Tokenization Constraints In Llms: A Study Of Symbolic And Arithmetic Reasoning Limits'
authors: Xiang Zhang, Juntai Cao, Jiaqi Wei, Yiwei Xu, Chenyu You
conference: "Arxiv"
year: 2025
bibkey: zhang2025tokenization
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14178'}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Merging', 'Prompting', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods']
---
Tokenization is the first - and often underappreciated - layer of computation in language models. While Chain-of-Thought (CoT) prompting enables transformer models to approximate recurrent computation by externalizing intermediate steps, we show that the success of such reasoning is fundamentally bounded by the structure of tokenized inputs. This work presents a theoretical and empirical investigation into how tokenization schemes, particularly subword-based methods like byte-pair encoding (BPE), impede symbolic computation by merging or obscuring atomic reasoning units. We introduce the notion of Token Awareness to formalize how poor token granularity disrupts logical alignment and prevents models from generalizing symbolic procedures. Through systematic evaluation on arithmetic and symbolic tasks, we demonstrate that token structure dramatically affect reasoning performance, causing failure even with CoT, while atomically-aligned formats unlock strong generalization, allowing small models (e.g., GPT-4o-mini) to outperform larger systems (e.g., o1) in structured reasoning. Our findings reveal that symbolic reasoning ability in LLMs is not purely architectural, but deeply conditioned on token-level representations.
