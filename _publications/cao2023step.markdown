---
layout: publication
title: A Step Closer to Comprehensive Answers Constrained Multi-Stage Question Decomposition with Large Language Models
authors: Cao Hejing, An Zhenwei, Feng Jiazhan, Xu Kun, Chen Liwei, Zhao Dongyan
conference: "Arxiv"
year: 2023
bibkey: cao2023step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07491"}
  - {name: "Code", url: "https://github.com/alkaidpku/DQ-ToolQA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Tools']
---
While large language models exhibit remarkable performance in the Question Answering task they are susceptible to hallucinations. Challenges arise when these models grapple with understanding multi-hop relations in complex questions or lack the necessary knowledge for a comprehensive response. To address this issue we introduce the Decompose-and-Query framework (DQ). This framework guides the model to think and utilize external knowledge similar to ReAct while also restricting its thinking to reliable information effectively mitigating the risk of hallucinations. Experiments confirm the effectiveness of DQ On our ChitChatQA dataset DQ does not lose to ChatGPT in 67 of cases; on the HotPotQA question-only setting DQ achieved an F1 score of 59.6. Our code is available at https://github.com/alkaidpku/DQ-ToolQA.
