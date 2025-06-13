---
layout: publication
title: 'QUPID: Quantified Understanding For Enhanced Performance, Insights, And Decisions In Korean Search Engines'
authors: Ohjoon Kwon, Changsu Lee, Jihye Back, Lim Sun Suk, Inho Kang, Donghyeon Jeon
conference: "ACL 2025 Industry Track"
year: 2025
bibkey: kwon2025quantified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07345"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have been widely used for relevance assessment in information retrieval. However, our study demonstrates that combining two distinct small language models (SLMs) with different architectures can outperform LLMs in this task. Our approach -- QUPID -- integrates a generative SLM with an embedding-based SLM, achieving higher relevance judgment accuracy while reducing computational costs compared to state-of-the-art LLM solutions. This computational efficiency makes QUPID highly scalable for real-world search systems processing millions of queries daily. In experiments across diverse document types, our method demonstrated consistent performance improvements (Cohen's Kappa of 0.646 versus 0.387 for leading LLMs) while offering 60x faster inference times. Furthermore, when integrated into production search pipelines, QUPID improved nDCG@5 scores by 1.9%. These findings underscore how architectural diversity in model combinations can significantly enhance both search relevance and operational efficiency in information retrieval systems.
