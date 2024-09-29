---
layout: publication
title: A Symmetric Dual Encoding Dense Retrieval Framework For Knowledge-intensive Visual Question Answering
authors: Salemi Alireza, Pizzorno Juan Altmayer, Zamani Hamed
conference: "Arxiv"
year: 2023
bibkey: salemi2023symmetric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.13649"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Merging', 'Tools']
---
Knowledge-Intensive Visual Question Answering (KI-VQA) refers to answering a question about an image whose answer does not lie in the image. This paper presents a new pipeline for KI-VQA tasks consisting of a retriever and a reader. First we introduce DEDR a symmetric dual encoding dense retrieval framework in which documents and queries are encoded into a shared embedding space using uni-modal (textual) and multi-modal encoders. We introduce an iterative knowledge distillation approach that bridges the gap between the representation spaces in these two encoders. Extensive evaluation on two well-established KI-VQA datasets i.e. OK-VQA and FVQA suggests that DEDR outperforms state-of-the-art baselines by 11.637; and 30.937; on OK-VQA and FVQA respectively. Utilizing the passages retrieved by DEDR we further introduce MM-FiD an encoder-decoder multi-modal fusion-in-decoder model for generating a textual answer for KI-VQA tasks. MM-FiD encodes the question the image and each retrieved passage separately and uses all passages jointly in its decoder. Compared to competitive baselines in the literature this approach leads to 5.537; and 8.537; improvements in terms of question answering accuracy on OK-VQA and FVQA respectively.
