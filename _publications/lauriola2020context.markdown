---
layout: publication
title: Context-based Transformer Models for Answer Sentence Selection
authors: Lauriola Ivano, Moschitti Alessandro
conference: "Arxiv"
year: 2020
bibkey: lauriola2020context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.01285"}
tags: ['ARXIV', 'Model Architecture', 'Tools', 'Transformer']
---
An important task for the design of Question Answering systems is the selection of the sentence containing (or constituting) the answer from documents relevant to the asked question. Most previous work has only used the target sentence to compute its score with the question as the models were not powerful enough to also effectively encode additional contextual information. In this paper we analyze the role of the contextual information in the sentence selection task proposing a Transformer based architecture that leverages two types of contexts local and global. The former describes the paragraph containing the sentence aiming at solving implicit references whereas the latter describes the entire document containing the candidate sentence providing content-based information. The results on three different benchmarks show that the combination of local and global contexts in a Transformer model significantly improves the accuracy in Answer Sentence Selection.
