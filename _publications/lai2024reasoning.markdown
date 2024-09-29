---
layout: publication
title: RVISA Reasoning And Verification For Implicit Sentiment Analysis
authors: Lai Wenna, Xie Haoran, Xu Guandong, Li Qing
conference: "Arxiv"
year: 2024
bibkey: lai2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02340"}
tags: ['Applications', 'Prompting', 'Tools']
---
With an increasing social demand for fine45;grained sentiment analysis (SA) implicit sentiment analysis (ISA) poses a significant challenge with the absence of salient cue words in expressions. It necessitates reliable reasoning to understand how the sentiment is aroused and thus determine implicit sentiments. In the era of Large Language Models (LLMs) Encoder45;Decoder (ED) LLMs have gained popularity to serve as backbone models for SA applications considering impressive text comprehension and reasoning ability among diverse tasks. On the other hand Decoder45;only (DO) LLMs exhibit superior natural language generation and in45;context learning capabilities. However their responses may contain misleading or inaccurate information. To identify implicit sentiment with reliable reasoning this study proposes RVISA a two45;stage reasoning framework that harnesses the generation ability of DO LLMs and the reasoning ability of ED LLMs to train an enhanced reasoner. Specifically we adopt three45;hop reasoning prompting to explicitly furnish sentiment elements as cues. The generated rationales are utilized to fine45;tune an ED LLM into a skilled reasoner. Additionally we develop a straightforward yet effective verification mechanism to ensure the reliability of the reasoning learning. We evaluated the proposed method on two benchmark datasets and achieved state45;of45;the45;art results in ISA performance.
