---
layout: publication
title: 'Chain-of-thought Poisoning Attacks Against R1-based Retrieval-augmented Generation Systems'
authors: Hongru Song, Yu-an Liu, Ruqing Zhang, Jiafeng Guo, Yixing Fan
conference: "Arxiv"
year: 2025
bibkey: song2025chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16367'}
tags: ['RAG', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) systems can effectively mitigate the hallucination problem of large language models (LLMs),but they also possess inherent vulnerabilities. Identifying these weaknesses before the large-scale real-world deployment of RAG systems is of great importance, as it lays the foundation for building more secure and robust RAG systems in the future. Existing adversarial attack methods typically exploit knowledge base poisoning to probe the vulnerabilities of RAG systems, which can effectively deceive standard RAG models. However, with the rapid advancement of deep reasoning capabilities in modern LLMs, previous approaches that merely inject incorrect knowledge are inadequate when attacking RAG systems equipped with deep reasoning abilities. Inspired by the deep thinking capabilities of LLMs, this paper extracts reasoning process templates from R1-based RAG systems, uses these templates to wrap erroneous knowledge into adversarial documents, and injects them into the knowledge base to attack RAG systems. The key idea of our approach is that adversarial documents, by simulating the chain-of-thought patterns aligned with the model's training signals, may be misinterpreted by the model as authentic historical reasoning processes, thus increasing their likelihood of being referenced. Experiments conducted on the MS MARCO passage ranking dataset demonstrate the effectiveness of our proposed method.
