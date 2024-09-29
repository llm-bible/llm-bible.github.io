---
layout: publication
title: Query Rewriting For Retrieval45;augmented Large Language Models
authors: Ma Xinbei, Gong Yeyun, He Pengcheng, Zhao Hai, Duan Nan
conference: "Arxiv"
year: 2023
bibkey: ma2023query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14283"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) play powerful black45;box readers in the retrieve45;then45;read pipeline making remarkable progress in knowledge45;intensive tasks. This work introduces a new framework Rewrite45;Retrieve45;Read instead of the previous retrieve45;then45;read for the retrieval45;augmented LLMs from the perspective of the query rewriting. Unlike prior studies focusing on adapting either the retriever or the reader our approach pays attention to the adaptation of the search query itself for there is inevitably a gap between the input text and the needed knowledge in retrieval. We first prompt an LLM to generate the query then use a web search engine to retrieve contexts. Furthermore to better align the query to the frozen modules we propose a trainable scheme for our pipeline. A small language model is adopted as a trainable rewriter to cater to the black45;box LLM reader. The rewriter is trained using the feedback of the LLM reader by reinforcement learning. Evaluation is conducted on downstream tasks open45;domain QA and multiple45;choice QA. Experiments results show consistent performance improvement indicating that our framework is proven effective and scalable and brings a new framework for retrieval45;augmented LLM.
