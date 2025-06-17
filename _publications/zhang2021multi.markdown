---
layout: publication
title: Multi-turn Dialogue Reading Comprehension With Pivot Turns And Knowledge
authors: Zhuosheng Zhang, Junlong Li, Hai Zhao
conference: Arxiv
year: 2021
citations: 15
bibkey: zhang2021multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.05474'}]
tags: [Transformer]
---
Multi-turn dialogue reading comprehension aims to teach machines to read
dialogue contexts and solve tasks such as response selection and answering
questions. The major challenges involve noisy history contexts and especial
prerequisites of commonsense knowledge that is unseen in the given material.
Existing works mainly focus on context and response matching approaches. This
work thus makes the first attempt to tackle the above two challenges by
extracting substantially important turns as pivot utterances and utilizing
external knowledge to enhance the representation of context. We propose a
pivot-oriented deep selection model (PoDS) on top of the Transformer-based
language models for dialogue comprehension. In detail, our model first picks
out the pivot utterances from the conversation history according to the
semantic matching with the candidate response or question, if any. Besides,
knowledge items related to the dialogue context are extracted from a knowledge
graph as external knowledge. Then, the pivot utterances and the external
knowledge are combined with a well-designed mechanism for refining predictions.
Experimental results on four dialogue comprehension benchmark tasks show that
our proposed model achieves great improvements on baselines. A series of
empirical comparisons are conducted to show how our selection strategies and
the extra knowledge injection influence the results.