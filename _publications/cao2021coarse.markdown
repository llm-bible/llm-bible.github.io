---
layout: publication
title: Coarse45;grained Decomposition And Fine45;grained Interaction For Multi45;hop Question Answering
authors: Cao Xing, Liu Yun
conference: "Arxiv"
year: 2021
bibkey: cao2021coarse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.05988"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
Recent advances regarding question answering and reading comprehension have resulted in models that surpass human performance when the answer is contained in a single continuous passage of text requiring only single45;hop reasoning. However in actual scenarios lots of complex queries require multi45;hop reasoning. The key to the Question Answering task is semantic feature interaction between documents and questions which is widely processed by Bi45;directional Attention Flow (Bi45;DAF) but Bi45;DAF generally captures only the surface semantics of words in complex questions and fails to capture implied semantic feature of intermediate answers. As a result Bi45;DAF partially ignores part of the contexts related to the question and cannot extract the most important parts of multiple documents. In this paper we propose a new model architecture for multi45;hop question answering by applying two completion strategies (1) Coarse45;Grain complex question Decomposition (CGDe) strategy are introduced to decompose complex question into simple ones under the condition of without any additional annotations (2) Fine45;Grained Interaction (FGIn) strategy are introduced to better represent each word in the document and extract more comprehensive and accurate sentences related to the inference path. The above two strategies are combined and tested on the SQuAD and HotpotQA datasets and the experimental results show that our method outperforms state45;of45;the45;art baselines.
