---
layout: publication
title: Teaching Language Models To Hallucinate Less With Synthetic Tasks
authors: Jones Erik, Palangi Hamid, Simões Clarisse, Chandrasekaran Varun, Mukherjee Subhabrata, Mitra Arindam, Awadallah Ahmed, Kamar Ece
conference: "Arxiv"
year: 2023
bibkey: jones2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06827"}
tags: ['Applications', 'Efficiency And Optimization', 'Reinforcement Learning']
---
Large language models (LLMs) frequently hallucinate on abstractive summarization tasks such as document45;based question45;answering meeting summarization and clinical report generation even though all necessary information is included in context. However optimizing LLMs to hallucinate less on these tasks is challenging as hallucination is hard to efficiently evaluate at each optimization step. In this work we show that reducing hallucination on a synthetic task can also reduce hallucination on real45;world downstream tasks. Our method SynTra first designs a synthetic task where hallucinations are easy to elicit and measure. It next optimizes the LLMs system message via prefix45;tuning on the synthetic task and finally transfers the system message to realistic hard45;to45;optimize tasks. Across three realistic abstractive summarization tasks SynTra reduces hallucination for two 13B45;parameter LLMs using only a synthetic retrieval task for supervision. We also find that optimizing the system message rather than the model weights can be critical; fine45;tuning the entire model on the synthetic task can counterintuitively increase hallucination. Overall SynTra demonstrates that the extra flexibility of working with synthetic data can help mitigate undesired behaviors in practice.
