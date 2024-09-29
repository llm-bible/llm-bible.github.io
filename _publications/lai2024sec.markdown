---
layout: publication
title: SEC45;QA A Systematic Evaluation Corpus For Financial QA
authors: Lai Viet Dac, Krumdick Michael, Lovering Charles, Reddy Varshini, Schmidt Craig, Tanner Chris
conference: "Arxiv"
year: 2024
bibkey: lai2024sec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14394"}
tags: ['Applications', 'Ethics And Bias', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The financial domain frequently deals with large numbers of long documents that are essential for daily operations. Significant effort is put towards automating financial data analysis. However a persistent challenge not limited to the finance domain is the scarcity of datasets that accurately reflect real45;world tasks for model evaluation. Existing datasets are often constrained by size context or relevance to practical applications. Moreover LLMs are currently trained on trillions of tokens of text limiting access to novel data or documents that models have not encountered during training for unbiased evaluation. We propose SEC45;QA a continuous dataset generation framework with two key features 1) the semi45;automatic generation of Question45;Answer (QA) pairs spanning multiple long context financial documents which better represent real45;world financial scenarios; 2) the ability to continually refresh the dataset using the most recent public document collections not yet ingested by LLMs. Our experiments show that current retrieval augmented generation methods systematically fail to answer these challenging multi45;document questions. In response we introduce a QA system based on program45;of45;thought that improves the ability to perform complex information retrieval and quantitative reasoning pipelines thereby increasing QA accuracy.
