---
layout: publication
title: 'R2-KG: General-purpose Dual-agent Framework For Reliable Reasoning On Knowledge Graphs'
authors: Sumin Jo, Junseong Choi, Jiho Kim, Edward Choi
conference: "Arxiv"
year: 2025
bibkey: jo2025general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12767"}
  - {name: "Code", url: "https://github.com/ekrxjwh2009/R2-KG/"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Has Code', 'Applications']
---
Recent studies have combined Large Language Models (LLMs) with Knowledge Graphs (KGs) to enhance reasoning, improving inference accuracy without additional training while mitigating hallucination. However, existing frameworks still suffer two practical drawbacks: they must be re-tuned whenever the KG or reasoning task changes, and they depend on a single, high-capacity LLM for reliable (i.e., trustworthy) reasoning. To address this, we introduce R2-KG, a plug-and-play, dual-agent framework that separates reasoning into two roles: an Operator (a low-capacity LLM) that gathers evidence and a Supervisor (a high-capacity LLM) that makes final judgments. This design is cost-efficient for LLM inference while still maintaining strong reasoning accuracy. Additionally, R2-KG employs an Abstention mechanism, generating answers only when sufficient evidence is collected from KG, which significantly enhances reliability. Experiments across five diverse benchmarks show that R2-KG consistently outperforms baselines in both accuracy and reliability, regardless of the inherent capability of LLMs used as the Operator. Further experiments reveal that the single-agent version of R2-KG, equipped with a strict self-consistency strategy, achieves significantly higher-than-baseline reliability with reduced inference cost but increased abstention rate in complex KGs. Our findings establish R2-KG as a flexible and cost-effective solution for KG-based reasoning, reducing reliance on high-capacity LLMs while ensuring trustworthy inference. The code is available at https://github.com/ekrxjwh2009/R2-KG/.
