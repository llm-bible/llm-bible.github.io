---
layout: publication
title: 'Multilingual Needle In A Haystack: Investigating Long-context Behavior Of Multilingual Large Language Models'
authors: Hengle Amey, Bajpai Prasoon, Dan Soham, Chakraborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: hengle2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10151"}
tags: ['Applications']
---
While recent large language models (LLMs) demonstrate remarkable abilities in responding to queries in diverse languages, their ability to handle long multilingual contexts is unexplored. As such, a systematic evaluation of the long-context capabilities of LLMs in multilingual settings is crucial, specifically in the context of information retrieval. To address this gap, we introduce the MultiLingual Needle-in-a-Haystack (MLNeedle) test, designed to assess a model's ability to retrieve relevant information (the needle) from a collection of multilingual distractor texts (the haystack). This test serves as an extension of the multilingual question-answering task, encompassing both monolingual and cross-lingual retrieval. We evaluate four state-of-the-art LLMs on MLNeedle. Our findings reveal that model performance can vary significantly with language and needle position. Specifically, we observe that model performance is the lowest when the needle is (i) in a language outside the English language family and (ii) located in the middle of the input context. Furthermore, although some models claim a context size of \(8k\) tokens or greater, none demonstrate satisfactory cross-lingual retrieval performance as the context length increases. Our analysis provides key insights into the long-context behavior of LLMs in multilingual settings to guide future evaluation protocols. To our knowledge, this is the first study to investigate the multilingual long-context behavior of LLMs.
