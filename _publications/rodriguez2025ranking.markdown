---
layout: publication
title: 'Rankalign: A Ranking View Of The Generator-validator Gap In Large Language Models'
authors: Juan Diego Rodriguez, Wenxuan Ding, Katrin Erk, Greg Durrett
conference: "Arxiv"
year: 2025
bibkey: rodriguez2025ranking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11381'}
tags: ['RAG', 'Prompting', 'Applications', 'Training Techniques']
---
Although large language models (LLMs) have become generally more capable and
accurate across many tasks, some fundamental sources of unreliability remain in
their behavior. One key limitation is their inconsistency at reporting the the
same information when prompts are changed. In this paper, we consider the
discrepancy between a model's generated answer and their own verification of
that answer, the generator-validator gap. We define this gap in a more
stringent way than prior work: we expect correlation of scores from a generator
and a validator over the entire set of candidate answers. We show that
according to this measure, a large gap exists in various settings, including
question answering, lexical semantics tasks, and next-word prediction. We then
propose RankAlign, a ranking-based training method, and show that it
significantly closes the gap by 31.8% on average, surpassing all baseline
methods. Moreover, this approach generalizes well to out-of-domain tasks and
lexical items.
