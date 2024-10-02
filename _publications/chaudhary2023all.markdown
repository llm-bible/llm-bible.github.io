---
layout: publication
title: 'It''s All Relative! -- A Synthetic Query Generation Approach For Improving Zero-shot Relevance Prediction'
authors: Chaudhary Aditi, Raman Karthik, Bendersky Michael
conference: "Arxiv"
year: 2023
bibkey: chaudhary2023all
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07930"}
tags: ['Ethics And Bias', 'Prompting', 'Training Techniques']
---
Recent developments in large language models (LLMs) have shown promise in their ability to generate synthetic query-document pairs by prompting with as few as 8 demonstrations. This has enabled building better IR models, especially for tasks with no training data readily available. Typically, such synthetic query generation (QGen) approaches condition on an input context (e.g. a text document) and generate a query relevant to that context, or condition the QGen model additionally on the relevance label (e.g. relevant vs irrelevant) to generate queries across relevance buckets. However, we find that such QGen approaches are sub-optimal as they require the model to reason about the desired label and the input from a handful of examples. In this work, we propose to reduce this burden of LLMs by generating queries simultaneously for different labels. We hypothesize that instead of asking the model to generate, say, an irrelevant query given an input context, asking the model to generate an irrelevant query relative to a relevant query is a much simpler task setup for the model to reason about. Extensive experimentation across seven IR datasets shows that synthetic queries generated in such a fashion translates to a better downstream performance, suggesting that the generated queries are indeed of higher quality.
