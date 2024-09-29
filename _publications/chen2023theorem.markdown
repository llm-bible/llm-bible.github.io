---
layout: publication
title: "Theoremqa: A Theorem-driven Question Answering Dataset"
authors: Chen Wenhu, Yin Ming, Ku Max, Lu Pan, Wan Yixin, Ma Xueguang, Xu Jianyu, Wang Xinyi, Xia Tony
conference: "Arxiv"
year: 2023
bibkey: chen2023theorem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12524"}
  - {name: "Code", url: "https://github.com/wenhuchen/TheoremQA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG']
---
The recent LLMs like GPT-4 and PaLM-2 have made tremendous progress in solving fundamental math problems like GSM8K by achieving over 9037; accuracy. However their capabilities to solve more challenging math problems which require domain-specific knowledge (i.e. theorem) have yet to be investigated. In this paper we introduce TheoremQA the first theorem-driven question-answering dataset designed to evaluate AI models capabilities to apply theorems to solve challenging science problems. TheoremQA is curated by domain experts containing 800 high-quality questions covering 350 theorems (e.g. Taylors theorem Lagranges theorem Huffman coding Quantum Theorem Elasticity Theorem etc) from Math Physics EEamp;CS and Finance. We evaluate a wide spectrum of 16 large language and code models with different prompting strategies like Chain-of-Thoughts and Program-of-Thoughts. We found that GPT-4s capabilities to solve these problems are unparalleled achieving an accuracy of 5137; with Program-of-Thoughts Prompting. All the existing open-sourced models are below 1537; barely surpassing the random-guess baseline. Given the diversity and broad coverage of TheoremQA we believe it can be used as a better benchmark to evaluate LLMs capabilities to solve challenging science problems. The data and code are released in https://github.com/wenhuchen/TheoremQA."
