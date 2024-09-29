---
layout: publication
title: 'Self-moe: Towards Compositional Large Language Models With Self-specialized Experts'
authors: Kang Junmo, Karlinsky Leonid, Luo Hongyin, Wang Zhen, Hansen Jacob, Glass James, Cox David, Panda Rameswar, Feris Rogerio, Ritter Alan
conference: "Arxiv"
year: 2024
bibkey: kang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12034"}
tags: ['Interpretability And Explainability', 'Merging', 'Pretraining Methods', 'RAG']
---
We present Self-MoE an approach that transforms a monolithic LLM into a compositional modular system of self-specialized experts named MiXSE (MiXture of Self-specialized Experts). Our approach leverages self-specialization which constructs expert modules using self-generated synthetic data each equipped with a shared base LLM and incorporating self-optimized routing. This allows for dynamic and capability-specific handling of various target tasks enhancing overall capabilities without extensive human-labeled data and added parameters. Our empirical results reveal that specializing LLMs may exhibit potential trade-offs in performances on non-specialized tasks. On the other hand our Self-MoE demonstrates substantial improvements over the base LLM across diverse benchmarks such as knowledge reasoning math and coding. It also consistently outperforms other methods including instance merging and weight merging while offering better flexibility and interpretability by design with semantic experts and routing. Our findings highlight the critical role of modularity and the potential of self-improvement in achieving efficient scalable and adaptable systems.
