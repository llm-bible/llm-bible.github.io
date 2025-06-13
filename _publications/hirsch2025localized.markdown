---
layout: publication
title: 'Laquer: Localized Attribution Queries In Content-grounded Generation'
authors: Eran Hirsch, Aviv Slobodkin, David Wan, Elias Stengel-eskin, Mohit Bansal, Ido Dagan
conference: "Arxiv"
year: 2025
bibkey: hirsch2025localized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01187"}
tags: ['Tools', 'Applications', 'RAG', 'Language Modeling', 'Prompting']
---
Grounded text generation models often produce content that deviates from their source material, requiring user verification to ensure accuracy. Existing attribution methods associate entire sentences with source documents, which can be overwhelming for users seeking to fact-check specific claims. In contrast, existing sub-sentence attribution methods may be more precise but fail to align with users' interests. In light of these limitations, we introduce Localized Attribution Queries (LAQuer), a new task that localizes selected spans of generated output to their corresponding source spans, allowing fine-grained and user-directed attribution. We compare two approaches for the LAQuer task, including prompting large language models (LLMs) and leveraging LLM internal representations. We then explore a modeling framework that extends existing attributed text generation methods to LAQuer. We evaluate this framework across two grounded text generation tasks: Multi-document Summarization (MDS) and Long-form Question Answering (LFQA). Our findings show that LAQuer methods significantly reduce the length of the attributed text. Our contributions include: (1) proposing the LAQuer task to enhance attribution usability, (2) suggesting a modeling framework and benchmarking multiple baselines, and (3) proposing a new evaluation setting to promote future research on localized attribution in content-grounded generation.
