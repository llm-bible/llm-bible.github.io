---
layout: publication
title: 'Reppl: Recalibrating Perplexity By Uncertainty In Semantic Propagation And Language Generation For Explainable QA Hallucination Detection'
authors: Yiming May Huang, Junyan May Zhang, Zihao May Wang, Biquan May Bie, Xuming May Hu, Yi May R., Fung, Xinlei He
conference: "Arxiv"
year: 2025
bibkey: huang2025recalibrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15386'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'ACL', 'RAG', 'Security', 'Model Architecture', 'Prompting', 'TACL']
---
Large Language Models (LLMs) have become powerful, but hallucinations remain a vital obstacle to their trustworthy use. While previous works improved the capability of hallucination detection by measuring uncertainty, they all lack the ability to explain the provenance behind why hallucinations occur, i.e., which part of the inputs tends to trigger hallucinations. Recent works on the prompt attack indicate that uncertainty exists in semantic propagation, where attention mechanisms gradually fuse local token information into high-level semantics across layers. Meanwhile, uncertainty also emerges in language generation, due to its probability-based selection of high-level semantics for sampled generations. Based on that, we propose RePPL to recalibrate uncertainty measurement by these two aspects, which dispatches explainable uncertainty scores to each token and aggregates in Perplexity-style Log-Average form as total score. Experiments show that our method achieves the best comprehensive detection performance across various QA datasets on advanced models (average AUC of 0.833), and our method is capable of producing token-level uncertainty scores as explanations for the hallucination. Leveraging these scores, we preliminarily find the chaotic pattern of hallucination and showcase its promising usage.
