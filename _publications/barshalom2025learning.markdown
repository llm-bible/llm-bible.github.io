---
layout: publication
title: 'Learning On LLM Output Signatures For Gray-box Behavior Analysis'
authors: Guy Bar-shalom, Fabrizio Frasca, Derek Lim, Yoav Gelberg, Yftah Ziser, Ran El-yaniv, Gal Chechik, Haggai Maron
conference: "Arxiv"
year: 2025
bibkey: barshalom2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14043'}
  - {name: "Code", url: 'https://github.com/BarSGuy/LLM-Output-Signatures-Network'}
tags: ['Has Code', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have achieved widespread adoption, yet our understanding of their behavior remains limited, particularly in detecting data contamination and hallucinations. While recently proposed probing techniques provide insights through activation analysis, they require ``white-box'' access to model internals, often unavailable. Current ``gray-box'' approaches typically analyze only the probability of the actual tokens in the sequence with simple task-specific heuristics. Importantly, these methods overlook the rich information contained in the full token distribution at each processing step. To address these limitations, we propose that gray-box analysis should leverage the complete observable output of LLMs, consisting of both the previously used token probabilities as well as the complete token distribution sequences - a unified data type we term LOS (LLM Output Signature). To this end, we develop a transformer-based approach to process LOS that theoretically guarantees approximation of existing techniques while enabling more nuanced analysis. Our approach achieves superior performance on hallucination and data contamination detection in gray-box settings, significantly outperforming existing baselines. Furthermore, it demonstrates strong transfer capabilities across datasets and LLMs, suggesting that LOS captures fundamental patterns in LLM behavior. Our code is available at: https://github.com/BarSGuy/LLM-Output-Signatures-Network.
