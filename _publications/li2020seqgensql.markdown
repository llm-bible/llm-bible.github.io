---
layout: publication
title: Seqgensql 45;45; A Robust Sequence Generation Model For Structured Query Language
authors: Li Ning, Keller Bethany, Butler Mark, Cer Daniel
conference: "Arxiv"
year: 2020
bibkey: li2020seqgensql
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.03836"}
tags: ['Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
We explore using T5 (Raffel et al. (2019)) to directly translate natural language questions into SQL statements. General purpose natural language that interfaces to information stored within databases requires flexibly translating natural language questions into database queries. The best performing text45;to45;SQL systems approach this task by first converting questions into an intermediate logical form (LF) (Lyu et al. (2020)). While LFs provide a convenient intermediate representation and simplify query generation they introduce an additional layer of complexity and annotation requirements. However weakly supervised modeling that directly converts questions to SQL statements has proven more difficult without the scaffolding provided by LFs (Min et al. (2019)). We approach direct conversion of questions to SQL statements using T5 (Raffel et al. (2019)) a pre45;trained textto45;text generation model modified to support pointer45;generator style decoding (See et al. (2017)). We explore using question augmentation with table schema information and the use of automatically generated silver training data. The resulting model achieves 90.537; execution accuracy on the WikiSQL (Zhong et al. (2017)) test data set a new state45;of45;the45;art on weakly supervised SQL generation. The performance improvement is 6.637; absolute over the prior state45;of45;the45;art (Min et al. (2019)) and approaches the performance of state45;ofthe45;art systems making use of LFs.
