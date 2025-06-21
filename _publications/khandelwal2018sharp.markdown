---
layout: publication
title: 'Sharp Nearby, Fuzzy Far Away: How Neural Language Models Use Context'
authors: Urvashi Khandelwal, He He, Peng Qi, Dan Jurafsky
conference: Arxiv
year: 2018
citations: 109
bibkey: khandelwal2018sharp
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.04623'}]
tags: []
---
We know very little about how neural language models (LM) use prior
linguistic context. In this paper, we investigate the role of context in an
LSTM LM, through ablation studies. Specifically, we analyze the increase in
perplexity when prior context words are shuffled, replaced, or dropped. On two
standard datasets, Penn Treebank and WikiText-2, we find that the model is
capable of using about 200 tokens of context on average, but sharply
distinguishes nearby context (recent 50 tokens) from the distant history. The
model is highly sensitive to the order of words within the most recent
sentence, but ignores word order in the long-range context (beyond 50 tokens),
suggesting the distant past is modeled only as a rough semantic field or topic.
We further find that the neural caching model (Grave et al., 2017b) especially
helps the LSTM to copy words from within this distant context. Overall, our
analysis not only provides a better understanding of how neural LMs use their
context, but also sheds light on recent success from cache-based models.