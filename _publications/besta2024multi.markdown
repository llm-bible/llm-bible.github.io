---
layout: publication
title: Multi-Head RAG Solving Multi-Aspect Problems with LLMs
authors: Besta Maciej, Kubicek Ales, Niggli Roman, Gerstenberger Robert, Weitzendorf Lucas, Chi Mingyuan, Iff Patrick, Gajda Joanna, Nyczyk Piotr, Müller Jürgen, Niewiadomski Hubert, Chrapek Marcin, Podstawski Michał, Hoefler Torsten
conference: "Arxiv"
year: 2024
bibkey: besta2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05085"}
tags: ['ARXIV', 'LLM', 'Model Architecture', 'RAG', 'Tools', 'Transformer']
---
Retrieval Augmented Generation (RAG) enhances the abilities of Large Language Models (LLMs) by enabling the retrieval of documents into the LLM context to provide more accurate and relevant responses. Existing RAG solutions do not focus on queries that may require fetching multiple documents with substantially different contents. Such queries occur frequently but are challenging because the embeddings of these documents may be distant in the embedding space making it hard to retrieve them all. This paper introduces Multi-Head RAG (MRAG) a novel scheme designed to address this gap with a simple yet powerful idea leveraging activations of Transformers multi-head attention layer instead of the decoder layer as keys for fetching multi-aspect documents. The driving motivation is that different attention heads can learn to capture different data aspects. Harnessing the corresponding activations results in embeddings that represent various facets of data items and queries improving the retrieval accuracy for complex queries. We provide an evaluation methodology and metrics synthetic datasets and real-world use cases to demonstrate MRAGs effectiveness showing improvements of up to 20 in relevance over standard RAG baselines. MRAG can be seamlessly integrated with existing RAG frameworks and benchmarking tools like RAGAS as well as different classes of data stores.
