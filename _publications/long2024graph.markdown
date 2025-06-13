---
layout: publication
title: 'Got4rec: Graph Of Thoughts For Sequential Recommendation'
authors: Zewen Long, Liang Wang, Shu Wu, Qiang Liu, Liang Wang
conference: "Arxiv"
year: 2024
bibkey: long2024graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14922'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/GOT4Rec'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Prompting', 'Reinforcement Learning']
---
With their vast open-world knowledge and reasoning abilities, large language
models (LLMs) have become a promising tool for sequential recommendation.
Researchers have explored various methods to harness these capabilities, but
most existing approaches rely on simple input-output prompting, failing to
effectively bridge the gap between LLMs' general knowledge and the specific
needs of recommendation tasks. While reasoning strategies like chain-of-thought
(CoT) have been introduced to enhance performance, they often produce
inaccurate recommendations due to underutilized user preference information and
insufficient reasoning depth. To address these challenges, we propose GOT4Rec,
a novel sequential recommendation method leveraging the graph of thoughts (GoT)
reasoning strategy. Our method focuses on three key types of information in
user histories: short-term interests, long-term interests and collaborative
information from other users. It enables LLMs to reason independently and
generate recommendations, subsequently aggregating results to derive final
items. This method allows LLMs, with enhanced reasoning capabilities, to better
utilize the user sequence information, producing more accurate recommendations
and comprehensive explanations. Extensive experiments on real-world datasets
demonstrate the effectiveness of GOT4Rec, outperforming existing
state-of-the-art baselines with an average improvement of 37.11%. Our code is
available at https://anonymous.4open.science/r/GOT4Rec.
