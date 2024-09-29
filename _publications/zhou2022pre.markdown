---
layout: publication
title: Tacube Pre45;computing Data Cubes For Answering Numerical45;reasoning Questions Over Tabular Data
authors: Zhou Fan, Hu Mengkang, Dong Haoyu, Cheng Zhoujun, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2022
bibkey: zhou2022pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.12682"}
tags: ['Applications', 'Merging', 'RAG', 'Tools']
---
Existing auto45;regressive pre45;trained language models (PLMs) like T5 and BART have been well applied to table question answering by UNIFIEDSKG and TAPEX respectively and demonstrated state45;of45;the45;art results on multiple benchmarks. However auto45;regressive PLMs are challenged by recent emerging numerical reasoning datasets such as TAT45;QA due to the error45;prone implicit calculation. In this paper we present TaCube to pre45;compute aggregation/arithmetic results for the table in advance so that they are handy and readily available for PLMs to answer numerical reasoning questions. TaCube systematically and comprehensively covers a collection of computational operations over table segments. By simply concatenating TaCube to the input sequence of PLMs it shows significant experimental effectiveness. TaCube promotes the F1 score from 49.637; to 66.237; on TAT45;QA and achieves new state45;of45;the45;art results on WikiTQ (59.637; denotation accuracy). TaCubes improvements on numerical reasoning cases are even more notable on TAT45;QA TaCube promotes the exact match accuracy of BART45;large by 39.637; on sum 52.537; on average 36.637; on substraction and 22.237; on division. We believe that TaCube is a general and portable pre45;computation solution that can be potentially integrated to various numerical reasoning frameworks
