---
layout: publication
title: 'Context-based Quotation Recommendation'
authors: Ansel Maclaughlin, Tao Chen, Burcu Karagol Ayan, Dan Roth
conference: "Arxiv"
year: 2020
bibkey: maclaughlin2020context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.08319"}
tags: ['BERT', 'RAG', 'Model Architecture']
---
While composing a new document, anything from a news article to an email or
essay, authors often utilize direct quotes from a variety of sources. Although
an author may know what point they would like to make, selecting an appropriate
quote for the specific context may be time-consuming and difficult. We
therefore propose a novel context-aware quote recommendation system which
utilizes the content an author has already written to generate a ranked list of
quotable paragraphs and spans of tokens from a given source document.
  We approach quote recommendation as a variant of open-domain question
answering and adapt the state-of-the-art BERT-based methods from open-QA to our
task. We conduct experiments on a collection of speech transcripts and
associated news articles, evaluating models' paragraph ranking and span
prediction performances. Our experiments confirm the strong performance of
BERT-based methods on this task, which outperform bag-of-words and neural
ranking baselines by more than 30% relative across all ranking metrics.
Qualitative analyses show the difficulty of the paragraph and span
recommendation tasks and confirm the quotability of the best BERT model's
predictions, even if they are not the true selected quotes from the original
news articles.
