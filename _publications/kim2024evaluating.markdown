---
layout: publication
title: 'FABLES: Evaluating Faithfulness And Content Selection In Book-length Summarization'
authors: Yekyung Kim, Yapei Chang, Marzena Karpinska, Aparna Garimella, Varun Manjunatha, Kyle Lo, Tanya Goyal, Mohit Iyyer
conference: "1st Conference on Language Modeling (COLM 2024)"
year: 2024
bibkey: kim2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01261"}
tags: ['GPT', 'Applications', 'Model Architecture']
---
While long-context large language models (LLMs) can technically summarize
book-length documents (>100K tokens), the length and complexity of the
documents have so far prohibited evaluations of input-dependent aspects like
faithfulness. In this paper, we conduct the first large-scale human evaluation
of faithfulness and content selection on LLM-generated summaries of fictional
books. Our study mitigates the issue of data contamination by focusing on
summaries of books published in 2023 or 2024, and we hire annotators who have
fully read each book prior to the annotation task to minimize cost and
cognitive burden. We collect FABLES, a dataset of annotations on 3,158 claims
made in LLM-generated summaries of 26 books, at a cost of $5.2K USD, which
allows us to rank LLM summarizers based on faithfulness: Claude-3-Opus
significantly outperforms all closed-source LLMs, while the open-source Mixtral
is on par with GPT-3.5-Turbo. An analysis of the annotations reveals that most
unfaithful claims relate to events and character states, and they generally
require indirect reasoning over the narrative to invalidate. While LLM-based
auto-raters have proven reliable for factuality and coherence in other
settings, we implement several LLM raters of faithfulness and find that none
correlates strongly with human annotations, especially with regard to detecting
unfaithful claims. Our experiments suggest that detecting unfaithful claims is
an important future direction not only for summarization evaluation but also as
a testbed for long-context understanding. Finally, we move beyond faithfulness
by exploring content selection errors in book-length summarization: we develop
a typology of omission errors related to crucial narrative elements and also
identify a systematic over-emphasis on events occurring towards the end of the
book.
