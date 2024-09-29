---
layout: publication
title: Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models
authors: Wang Qingyue, Ding Liang, Cao Yanan, Tian Zhiliang, Wang Shi, Tao Dacheng, Guo Li
conference: "Arxiv"
year: 2023
bibkey: wang2023recursively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15022"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods']
---
Recently large language models (LLMs) such as GPT-4 stand out remarkable conversational abilities enabling them to engage in dynamic and contextually relevant dialogues across a wide range of topics. However given a long conversation these chatbots fail to recall past information and tend to generate inconsistent responses. To address this we propose to recursively generate summaries/ memory using large language models (LLMs) to enhance long-term memory ability. Specifically our method first stimulates LLMs to memorize small dialogue contexts and then recursively produce new memory using previous memory and following contexts. Finally the chatbot can easily generate a highly consistent response with the help of the latest memory. We evaluate our method on both open and closed LLMs and the experiments on the widely-used public dataset show that our method can generate more consistent responses in a long-context conversation. Also we show that our strategy could nicely complement both long-context (e.g. 8K and 16K) and retrieval-enhanced LLMs bringing further long-term dialogue performance. Notably our method is a potential solution to enable the LLM to model the extremely long context. The code and scripts will be released later.
