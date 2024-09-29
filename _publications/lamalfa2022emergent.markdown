---
layout: publication
title: Emergent Linguistic Structures In Neural Networks Are Fragile
authors: La Malfa Emanuele, Wicker Matthew, Kwiatkowska Marta
conference: "Arxiv"
year: 2022
bibkey: lamalfa2022emergent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17406"}
tags: ['BERT', 'Ethics And Bias', 'Model Architecture', 'RAG', 'Security', 'Tools']
---
Large Language Models (LLMs) have been reported to have strong performance on natural language processing tasks. However performance metrics such as accuracy do not measure the quality of the model in terms of its ability to robustly represent complex linguistic structures. In this paper focusing on the ability of language models to represent syntax we propose a framework to assess the consistency and robustness of linguistic representations. To this end we introduce measures of robustness of neural network models that leverage recent advances in extracting linguistic constructs from LLMs via probing tasks i.e. simple tasks used to extract meaningful information about a single facet of a language model such as syntax reconstruction and root identification. Empirically we study the performance of four LLMs across six different corpora on the proposed robustness measures by analysing their performance and robustness with respect to syntax-preserving perturbations. We provide evidence that context-free representation (e.g. GloVe) are in some cases competitive with context-dependent representations from modern LLMs (e.g. BERT) yet equally brittle to syntax-preserving perturbations. Our key observation is that emergent syntactic representations in neural networks are brittle. We make the code trained models and logs available to the community as a contribution to the debate about the capabilities of LLMs.
