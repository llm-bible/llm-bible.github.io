---
layout: publication
title: RA45;DIT Retrieval45;augmented Dual Instruction Tuning
authors: Lin Xi Victoria, Chen Xilun, Chen Mingda, Shi Weijia, Lomeli Maria, James Rich, Rodriguez Pedro, Kahn Jacob, Szilvasy Gergely, Lewis Mike, Zettlemoyer Luke, Yih Scott
conference: "Arxiv"
year: 2023
bibkey: lin2023ra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01352"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Retrieval45;augmented language models (RALMs) improve performance by accessing long45;tail and up45;to45;date knowledge from external data stores but are challenging to build. Existing approaches require either expensive retrieval45;specific modifications to LM pre45;training or use post45;hoc integration of the data store that leads to suboptimal performance. We introduce Retrieval45;Augmented Dual Instruction Tuning (RA45;DIT) a lightweight fine45;tuning methodology that provides a third option by retrofitting any LLM with retrieval capabilities. Our approach operates in two distinct fine45;tuning steps (1) one updates a pre45;trained LM to better use retrieved information while (2) the other updates the retriever to return more relevant results as preferred by the LM. By fine45;tuning over tasks that require both knowledge utilization and contextual awareness we demonstrate that each stage yields significant performance improvements and using both leads to additional gains. Our best model RA45;DIT 65B achieves state45;of45;the45;art performance across a range of knowledge45;intensive zero45; and few45;shot learning benchmarks significantly outperforming existing in45;context RALM approaches by up to +8.937; in 045;shot setting and +1.437; in 545;shot setting on average.
