---
layout: publication
title: 'Rulerag: Rule-guided Retrieval-augmented Generation With Language Models For Question Answering'
authors: Zhongwu Chen, Chengjin Xu, Dingmin Wang, Zhen Huang, Yong Dou, Xuhui Jiang, Jian Guo
conference: "Arxiv"
year: 2024
bibkey: chen2024rule
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22353"}
tags: ['RAG', 'Prompting', 'In-Context Learning', 'Applications']
---
Retrieval-augmented generation (RAG) has shown promising potential in
knowledge intensive question answering (QA). However, existing approaches only
consider the query itself, neither specifying the retrieval preferences for the
retrievers nor informing the generators of how to refer to the retrieved
documents for the answers, which poses a significant challenge to the QA
performance. To address these issues, we propose Rule-guided
Retrieval-Augmented Generation with LMs, which explicitly introduces rules for
in-context learning (RuleRAG-ICL) to guide retrievers to recall related
documents in the directions of rules and uniformly guide generators to reason
attributed by the same rules. Moreover, most existing RAG datasets were
constructed without considering rules and Knowledge Graphs (KGs) are recognized
as providing high-quality rules. Therefore, we construct five rule-aware RAG
benchmarks for QA, RuleQA, based on KGs to stress the significance of retrieval
and reasoning with rules. Experiments on RuleQA demonstrate RuleRAG-ICL
improves the retrieval quality of +89.2% in Recall@10 and answer accuracy of
+103.1% in Exact Match, and RuleRAG-FT yields more enhancement. In addition,
experiments on four existing RAG datasets show RuleRAG is also effective by
offering rules in RuleQA to them, further proving the generalization of rule
guidance in RuleRAG.
