---
layout: publication
title: 'Integrating Planning Into Single-turn Long-form Text Generation'
authors: Yi Liang, You Wu, Honglei Zhuang, Li Chen, Jiaming Shen, Yiling Jia, Zhen Qin, Sumit Sanghai, Xuanhui Wang, Carl Yang, Michael Bendersky
conference: "Arxiv"
year: 2024
bibkey: liang2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06203"}
tags: ['Applications', 'RAG', 'Language Modeling', 'Training Techniques', 'Prompting']
---
Generating high-quality, in-depth textual documents, such as academic papers,
news articles, Wikipedia entries, and books, remains a significant challenge
for Large Language Models (LLMs). In this paper, we propose to use planning to
generate long form content. To achieve our goal, we generate intermediate steps
via an auxiliary task that teaches the LLM to plan, reason and structure before
generating the final text. Our main novelty lies in a single auxiliary task
that does not require multiple rounds of prompting or planning. To overcome the
scarcity of training data for these intermediate steps, we leverage LLMs to
generate synthetic intermediate writing data such as outlines, key information
and summaries from existing full articles. Our experiments demonstrate on two
datasets from different domains, namely the scientific news dataset SciNews and
Wikipedia datasets in KILT-Wiki and FreshWiki, that LLMs fine-tuned with the
auxiliary task generate higher quality documents. We observed +2.5% improvement
in ROUGE-Lsum, and a strong 3.60 overall win/loss ratio via human SxS
evaluation, with clear wins in organization, relevance, and verifiability.
