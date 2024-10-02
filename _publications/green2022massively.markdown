---
layout: publication
title: 'Massively Multilingual Lexical Specialization Of Multilingual Transformers'
authors: Green Tommaso, Ponzetto Simone Paolo, Glavaš Goran
conference: "Arxiv"
year: 2022
bibkey: green2022massively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.01018"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
While pretrained language models (PLMs) primarily serve as general-purpose text encoders that can be fine-tuned for a wide variety of downstream tasks, recent work has shown that they can also be rewired to produce high-quality word representations (i.e., static word embeddings) and yield good performance in type-level lexical tasks. While existing work primarily focused on the lexical specialization of monolingual PLMs with immense quantities of monolingual constraints, in this work we expose massively multilingual transformers (MMTs, e.g., mBERT or XLM-R) to multilingual lexical knowledge at scale, leveraging BabelNet as the readily available rich source of multilingual and cross-lingual type-level lexical knowledge. Concretely, we use BabelNet's multilingual synsets to create synonym pairs (or synonym-gloss pairs) across 50 languages and then subject the MMTs (mBERT and XLM-R) to a lexical specialization procedure guided by a contrastive objective. We show that such massively multilingual lexical specialization brings substantial gains in two standard cross-lingual lexical tasks, bilingual lexicon induction and cross-lingual word similarity, as well as in cross-lingual sentence retrieval. Crucially, we observe gains for languages unseen in specialization, indicating that multilingual lexical specialization enables generalization to languages with no lexical constraints. In a series of subsequent controlled experiments, we show that the number of specialization constraints plays a much greater role than the set of languages from which they originate.
