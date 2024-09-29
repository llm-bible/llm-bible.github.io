---
layout: publication
title: Query2doc Query Expansion With Large Language Models
authors: Wang Liang, Yang Nan, Wei Furu
conference: "Arxiv"
year: 2023
bibkey: wang2023query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.07678"}
tags: ['Pretraining Methods', 'Prompting']
---
This paper introduces a simple yet effective query expansion approach denoted as query2doc to improve both sparse and dense retrieval systems. The proposed method first generates pseudo45;documents by few45;shot prompting large language models (LLMs) and then expands the query with generated pseudo45;documents. LLMs are trained on web45;scale text corpora and are adept at knowledge memorization. The pseudo45;documents from LLMs often contain highly relevant information that can aid in query disambiguation and guide the retrievers. Experimental results demonstrate that query2doc boosts the performance of BM25 by 337; to 1537; on ad45;hoc IR datasets such as MS45;MARCO and TREC DL without any model fine45;tuning. Furthermore our method also benefits state45;of45;the45;art dense retrievers in terms of both in45;domain and out45;of45;domain results.
