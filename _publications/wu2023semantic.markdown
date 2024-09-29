---
layout: publication
title: Semantic Parsing By Large Language Models For Intricate Updating Strategies Of Zero-shot Dialogue State Tracking
authors: Wu Yuxiang, Dong Guanting, Xu Weiran
conference: "Arxiv"
year: 2023
bibkey: wu2023semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10520"}
tags: ['In Context Learning', 'Prompting', 'RAG', 'Tools']
---
Zero-shot Dialogue State Tracking (DST) addresses the challenge of acquiring and annotating task-oriented dialogues which can be time-consuming and costly. However DST extends beyond simple slot-filling and requires effective updating strategies for tracking dialogue state as conversations progress. In this paper we propose ParsingDST a new In-Context Learning (ICL) method to introduce additional intricate updating strategies in zero-shot DST. Our approach reformulates the DST task by leveraging powerful Large Language Models (LLMs) and translating the original dialogue text to JSON through semantic parsing as an intermediate state. We also design a novel framework that includes more modules to ensure the effectiveness of updating strategies in the text-to-JSON process. Experimental results demonstrate that our approach outperforms existing zero-shot DST methods on MultiWOZ exhibiting significant improvements in Joint Goal Accuracy (JGA) and slot accuracy compared to existing ICL methods. Our code has been released.
