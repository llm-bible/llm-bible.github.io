---
layout: publication
title: 'Multi-hop Question Generation With Graph Convolutional Network'
authors: Dan Su et al.
conference: "Arxiv"
year: 2020
citations: 35
bibkey: su2020multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2010.09240'}
  - {name: "Code", url: 'https://github.com/HLTCHKUST/MulQG}{https://github.com/HLTCHKUST/MulQG'}
tags: ['RAG', 'Has Code', 'Merging']
---
Multi-hop Question Generation (QG) aims to generate answer-related questions
by aggregating and reasoning over multiple scattered evidence from different
paragraphs. It is a more challenging yet under-explored task compared to
conventional single-hop QG, where the questions are generated from the sentence
containing the answer or nearby sentences in the same paragraph without complex
reasoning. To address the additional challenges in multi-hop QG, we propose
Multi-Hop Encoding Fusion Network for Question Generation (MulQG), which does
context encoding in multiple hops with Graph Convolutional Network and encoding
fusion via an Encoder Reasoning Gate. To the best of our knowledge, we are the
first to tackle the challenge of multi-hop reasoning over paragraphs without
any sentence-level information. Empirical results on HotpotQA dataset
demonstrate the effectiveness of our method, in comparison with baselines on
automatic evaluation metrics. Moreover, from the human evaluation, our proposed
model is able to generate fluent questions with high completeness and
outperforms the strongest baseline by 20.8% in the multi-hop evaluation. The
code is publicly available at
https://github.com/HLTCHKUST/MulQG\}\{https://github.com/HLTCHKUST/MulQG .
