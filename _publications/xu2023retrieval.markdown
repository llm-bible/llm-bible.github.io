---
layout: publication
title: Retrieval-based Video Language Model For Efficient Long Video Question Answering
authors: Xu Jiaqi, Lan Cuiling, Xie Wenxuan, Chen Xuejin, Lu Yan
conference: "Arxiv"
year: 2023
bibkey: xu2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04931"}
tags: ['Applications', 'Tools']
---
The remarkable natural language understanding reasoning and generation capabilities of large language models (LLMs) have made them attractive for application to video question answering (Video QA) tasks utilizing video tokens as contextual input. However employing LLMs for long video understanding presents significant challenges and remains under-explored. The extensive number of video tokens leads to considerable computational costs for LLMs while using aggregated tokens results in loss of vision details. Moreover the presence of abundant question-irrelevant tokens introduces noise to the video QA process. To address these issues we introduce a simple yet effective retrieval-based video language model (R-VLM) for efficient and interpretable long video QA. Specifically given a question (query) and a long video our model identifies and selects the most relevant K video chunks and uses their associated visual tokens to serve as context for the LLM inference. This effectively reduces the number of video tokens eliminates noise interference and enhances system performance. Our experimental results validate the effectiveness of our framework for comprehending long videos. Furthermore based on the retrieved chunks our model is interpretable that provides the justifications on where we get the answers.
