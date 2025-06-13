---
layout: publication
title: 'CPRM: A Llm-based Continual Pre-training Framework For Relevance Modeling In Commercial Search'
authors: Kaixin Wu, Yixin Ji, Zeyuan Chen, Qiang Wang, Cunxiang Wang, Hong Liu, Baijun Ji, Jia Xu, Zhongyi Liu, Jinjie Gu, Yuan Zhou, Linjian Mo
conference: "Arxiv"
year: 2024
bibkey: wu2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01269'}
tags: ['Training Techniques', 'Tools', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Relevance modeling between queries and items stands as a pivotal component in
commercial search engines, directly affecting the user experience. Given the
remarkable achievements of large language models (LLMs) in various natural
language processing (NLP) tasks, LLM-based relevance modeling is gradually
being adopted within industrial search systems. Nevertheless, foundational LLMs
lack domain-specific knowledge and do not fully exploit the potential of
in-context learning. Furthermore, structured item text remains underutilized,
and there is a shortage in the supply of corresponding queries and background
knowledge. We thereby propose CPRM (Continual Pre-training for Relevance
Modeling), a framework designed for the continual pre-training of LLMs to
address these issues. Our CPRM framework includes three modules: 1) employing
both queries and multi-field item to jointly pre-train for enhancing domain
knowledge, 2) applying in-context pre-training, a novel approach where LLMs are
pre-trained on a sequence of related queries or items, and 3) conducting
reading comprehension on items to produce associated domain knowledge and
background information (e.g., generating summaries and corresponding queries)
to further strengthen LLMs. Results on offline experiments and online A/B
testing demonstrate that our model achieves convincing performance compared to
strong baselines.
