---
layout: publication
title: In45;context Pretraining Language Modeling Beyond Document Boundaries
authors: Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Gergely Szilvasy, Rich James, Xi Victoria Lin, Noah A. Smith, Luke Zettlemoyer, Scott Yih, Mike Lewis
conference: "Arxiv"
year: 2023
bibkey: shi2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2310.10638v6"}
tags: ['Language Modeling', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models (LMs) are currently trained to predict tokens given document prefixes enabling them to directly perform long45;form generation and prompting45;style tasks which can be reduced to document completion. Existing pretraining pipelines train LMs by concatenating random sets of short documents to create input contexts but the prior documents provide no signal for predicting the next document. We instead present In45;Context Pretraining a new approach where language models are pretrained on a sequence of related documents thereby explicitly encouraging them to read and reason across document boundaries. We can do In45;Context Pretraining by simply changing the document ordering so that each context contains related documents and directly applying existing pretraining pipelines. However this document sorting problem is challenging. There are billions of documents and we would like the sort to maximize contextual similarity for every document without repeating any data. To do this we introduce approximate algorithms for finding related documents with efficient nearest neighbor search and constructing coherent input contexts with a graph traversal algorithm. Our experiments show In45;Context Pretraining offers a simple and scalable approach to significantly enhance LMsperformance we see notable improvements in tasks that require more complex contextual reasoning including in45;context learning (+837;) reading comprehension (+1537;) faithfulness to previous contexts (+1637;) long45;context reasoning (+537;) and retrieval augmentation (+937;).
