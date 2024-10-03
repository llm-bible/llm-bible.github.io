---
layout: publication
title: 'CLAPNQ: Cohesive Long-form Answers From Passages In Natural Questions For RAG Systems'
authors: Rosenthal Sara, Sil Avirup, Florian Radu, Roukos Salim
conference: "Arxiv"
year: 2024
bibkey: rosenthal2024cohesive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02103"}
  - {name: "Code", url: "https://github.com/primeqa/clapnq"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) has become a popular application for large language models. It is preferable that successful RAG systems provide accurate answers that are supported by being grounded in a passage without any hallucinations. While considerable work is required for building a full RAG pipeline, being able to benchmark performance is also necessary. We present ClapNQ, a benchmark Long-form Question Answering dataset for the full RAG pipeline. ClapNQ includes long answers with grounded gold passages from Natural Questions (NQ) and a corpus to perform either retrieval, generation, or the full RAG pipeline. The ClapNQ answers are concise, 3x smaller than the full passage, and cohesive, with multiple pieces of the passage that are not contiguous. RAG models must adapt to these properties to be successful at ClapNQ. We present baseline experiments and analysis for ClapNQ that highlight areas where there is still significant room for improvement in grounded RAG. CLAPNQ is publicly available at https://github.com/primeqa/clapnq
