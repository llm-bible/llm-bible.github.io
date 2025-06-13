---
layout: publication
title: 'From Jack Of All Trades To Master Of One: Specializing Llm-based Autoraters To A Test Set'
authors: Mara Finkelstein, Dan Deutsch, Parker Riley, Juraj Juraska, Geza Kovacs, Markus Freitag
conference: "Arxiv"
year: 2024
bibkey: finkelstein2024from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15387'}
tags: ['RAG', 'WMT', 'Security', 'Applications', 'Prompting', 'In-Context Learning']
---
As LLMs continue to become more powerful and versatile, human evaluation has
quickly become intractable at scale and reliance on automatic metrics has
become the norm. Recently, it has been shown that LLMs are themselves
state-of-the-art evaluators for many tasks. These Autoraters are typically
designed so that they generalize to new systems and test sets. In practice,
however, evaluation is performed on a small set of fixed, canonical test sets,
which are carefully curated to measure certain capabilities of interest and are
not changed frequently. In this work, we design a method which specializes a
prompted Autorater to a given test set, by leveraging historical ratings on the
test set to construct in-context learning (ICL) examples. We evaluate our
Specialist method on the task of fine-grained machine translation evaluation,
and show that it dramatically outperforms the state-of-the-art XCOMET metric by
54% and 119% on the WMT'23 and WMT'24 test sets, respectively. We perform
extensive analyses to understand the representations learned by our Specialist
metrics, and how variability in rater behavior affects their performance. We
also verify the generalizability and robustness of our Specialist method for
designing automatic metrics across different numbers of ICL examples, LLM
backbones, systems to evaluate, and evaluation tasks.
