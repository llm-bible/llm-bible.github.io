---
layout: publication
title: Writing In The Margins\: Better Inference Pattern For Long Context Retrieval
authors: Russak Melisa, Jamil Umar, Bryant Christopher, Kamble Kiran, Magnuson Axel, Russak Mateusz, Alshikh Waseem
conference: "Arxiv"
year: 2024
bibkey: russak2024writing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14906"}
  - {name: "Code", url: "https://github.com/writer/writing-in-the-margins"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
In this paper we introduce Writing in the Margins (WiM) a new inference pattern for Large Language Models designed to optimize the handling of long input sequences in retrieval-oriented tasks. This approach leverages the chunked prefill of the key-value cache to perform segment-wise inference which enables efficient processing of extensive contexts along with the generation and classification of intermediate information (margins) that guide the model towards specific tasks. This method increases computational overhead marginally while significantly enhancing the performance of off-the-shelf models without the need for fine-tuning. Specifically we observe that WiM provides an average enhancement of 7.537; in accuracy for reasoning skills (HotpotQA MultiHop-RAG) and more than a 30.037; increase in the F1-score for aggregation tasks (CWE). Additionally we show how the proposed pattern fits into an interactive retrieval design that provides end-users with ongoing updates about the progress of context processing and pinpoints the integration of relevant information into the final response. We release our implementation of WiM using Hugging Face Transformers library at https://github.com/writer/writing-in-the-margins."
