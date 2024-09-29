---
layout: publication
title: Code4struct Code Generation For Few45;shot Event Structure Prediction
authors: Wang Xingyao, Li Sha, Ji Heng
conference: "Arxiv"
year: 2022
bibkey: wang2022code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.12810"}
tags: ['Applications', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language Model (LLM) trained on a mixture of text and code has demonstrated impressive capability in translating natural language (NL) into structured code. We observe that semantic structures can be conveniently translated into code and propose Code4Struct to leverage such text45;to45;structure translation capability to tackle structured prediction tasks. As a case study we formulate Event Argument Extraction (EAE) as converting text into event45;argument structures that can be represented as a class object using code. This alignment between structures and code enables us to take advantage of Programming Language (PL) features such as inheritance and type annotation to introduce external knowledge or add constraints. We show that with sufficient in45;context examples formulating EAE as a code generation problem is advantageous over using variants of text45;based prompts. Despite only using 20 training event instances for each event type Code4Struct is comparable to supervised models trained on 4202 instances and outperforms current state45;of45;the45;art (SOTA) trained on 2045;shot data by 29.537; absolute F1. Code4Struct can use 1045;shot training data from a sibling event type to predict arguments for zero45;resource event types and outperforms the zero45;shot baseline by 1237; absolute F1.
