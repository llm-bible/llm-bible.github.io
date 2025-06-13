---
layout: publication
title: 'Wixqa: A Multi-dataset Benchmark For Enterprise Retrieval-augmented Generation'
authors: Dvir Cohen, Lin Burg, Sviatoslav Pykhnivskyi, Hagit Gur, Stanislav Kovynov, Olga Atzmon, Gilad Barkan
conference: "Arxiv"
year: 2025
bibkey: cohen2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08643"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) is a cornerstone of modern question answering (QA) systems, enabling grounded answers based on external knowledge. Although recent progress has been driven by open-domain datasets, enterprise QA systems need datasets that mirror the concrete, domain-specific issues users raise in day-to-day support scenarios. Critically, evaluating end-to-end RAG systems requires benchmarks comprising not only question--answer pairs but also the specific knowledge base (KB) snapshot from which answers were derived. To address this need, we introduce WixQA, a benchmark suite featuring QA datasets precisely grounded in the released KB corpus, enabling holistic evaluation of retrieval and generation components. WixQA includes three distinct QA datasets derived from Wix.com customer support interactions and grounded in a snapshot of the public Wix Help Center KB: (i) WixQA-ExpertWritten, 200 real user queries with expert-authored, multi-step answers; (ii) WixQA-Simulated, 200 expert-validated QA pairs distilled from user dialogues; and (iii) WixQA-Synthetic, 6,222 LLM-generated QA pairs, with one pair systematically derived from each article in the knowledge base. We release the KB snapshot alongside the datasets under MIT license and provide comprehensive baseline results, forming a unique benchmark for evaluating enterprise RAG systems in realistic enterprise environments.
