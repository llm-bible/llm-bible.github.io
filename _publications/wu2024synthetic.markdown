---
layout: publication
title: 'Synthetic Multimodal Question Generation'
authors: Wu Ian, Jayanthi Sravan, Viswanathan Vijay, Rosenberg Simon, Pakazad Sina, Wu Tongshuang, Neubig Graham
conference: "Arxiv"
year: 2024
bibkey: wu2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02233"}
tags: ['Multimodal Models', 'RAG', 'Tools']
---
Multimodal Retrieval Augmented Generation (MMRAG) is a powerful approach to question-answering over multimodal documents. A key challenge with evaluating MMRAG is the paucity of high-quality datasets matching the question styles and modalities of interest. In light of this we propose SMMQG a synthetic data generation framework. SMMQG leverages interplay between a retriever large language model (LLM) and large multimodal model (LMM) to generate question and answer pairs directly from multimodal documents with the questions conforming to specified styles and modalities. We use SMMQG to generate an MMRAG dataset of 1024 questions over Wikipedia documents and evaluate state-of-the-art models using it revealing insights into model performance that are attainable only through style- and modality-specific evaluation data. Next we measure the quality of data produced by SMMQG via a human study. We find that the quality of our synthetic data is on par with the quality of the crowdsourced benchmark MMQA and that downstream evaluation results using both datasets strongly concur.
