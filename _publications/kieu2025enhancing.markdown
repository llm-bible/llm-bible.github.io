---
layout: publication
title: 'Enhancing News Recommendation With Hierarchical LLM Prompting'
authors: Hai-dang Kieu, Delvin Ce Zhang, Minh Duc Nguyen, Min Xu, Qiang Wu, Dung D. Le
conference: "Arxiv"
year: 2025
bibkey: kieu2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20452"}
tags: ['Prompting', 'Model Architecture', 'Transformer', 'Attention Mechanism']
---
Personalized news recommendation systems often struggle to effectively
capture the complexity of user preferences, as they rely heavily on shallow
representations, such as article titles and abstracts. To address this problem,
we introduce a novel method, namely PNR-LLM, for Large Language Models for
Personalized News Recommendation. Specifically, PNR-LLM harnesses the
generation capabilities of LLMs to enrich news titles and abstracts, and
consequently improves recommendation quality. PNR-LLM contains a novel module,
News Enrichment via LLMs, which generates deeper semantic information and
relevant entities from articles, transforming shallow contents into richer
representations. We further propose an attention mechanism to aggregate
enriched semantic- and entity-level data, forming unified user and news
embeddings that reveal a more accurate user-news match. Extensive experiments
on MIND datasets show that PNR-LLM outperforms state-of-the-art baselines.
Moreover, the proposed data enrichment module is model-agnostic, and we
empirically show that applying our proposed module to multiple existing models
can further improve their performance, verifying the advantage of our design.
