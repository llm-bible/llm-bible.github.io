---
layout: publication
title: 'IGSQL: Database Schema Interaction Graph Based Neural Model For Context-dependent
  Text-to-sql Generation'
authors: Yitao Cai, Xiaojun Wan
conference: Arxiv
year: 2020
citations: 17
bibkey: cai2020database
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.05744'}]
tags: []
---
Context-dependent text-to-SQL task has drawn much attention in recent years.
Previous models on context-dependent text-to-SQL task only concentrate on
utilizing historical user inputs. In this work, in addition to using encoders
to capture historical information of user inputs, we propose a database schema
interaction graph encoder to utilize historicalal information of database
schema items. In decoding phase, we introduce a gate mechanism to weigh the
importance of different vocabularies and then make the prediction of SQL
tokens. We evaluate our model on the benchmark SParC and CoSQL datasets, which
are two large complex context-dependent cross-domain text-to-SQL datasets. Our
model outperforms previous state-of-the-art model by a large margin and
achieves new state-of-the-art results on the two datasets. The comparison and
ablation results demonstrate the efficacy of our model and the usefulness of
the database schema interaction graph encoder.