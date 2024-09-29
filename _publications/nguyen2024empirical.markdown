---
layout: publication
title: An Empirical Study On Capability Of Large Language Models In Understanding Code Semantics
authors: Nguyen Thu-trang, Vu Thanh Trong, Vo Hieu Dinh, Nguyen Son
conference: "Arxiv"
year: 2024
bibkey: nguyen2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03611"}
tags: ['Applications', 'RAG', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models for Code (code LLMs) have demonstrated remarkable performance across various software engineering (SE) tasks increasing the application of code LLMs in software development. Despite the success of code LLMs there remain significant concerns about the actual capabilities and reliability of these models whether these models really learn the semantics of code from the training data and leverage the learned knowledge to perform the SE tasks. In this paper we introduce EMPICA a comprehensive framework designed to systematically and empirically evaluate the capabilities of code LLMs in understanding code semantics. Specifically EMPICA systematically introduces controlled modifications/transformations into the input code and examines the models responses. Generally code LLMs must be robust to semantically equivalent code inputs and be sensitive to non-equivalent ones for all SE tasks. Specifically for every SE task given an input code snippet c and its semantic equivalent variants code LLMs must robustly produce consistent/equivalent outputs while they are expected to generate different outputs for c and its semantic non-equivalent variants. Our experimental results on three representative code understanding tasks including code summarization method name prediction and output prediction reveal that the robustness and sensitivity of the state-of-the-art code LLMs to code transformations vary significantly across tasks and transformation operators. In addition the code LLMs exhibit better robustness to the semantic preserving transformations than their sensitivity to the semantic non-preserving transformations. These results highlight a need to enhance the models capabilities of understanding code semantics especially the sensitivity property.
