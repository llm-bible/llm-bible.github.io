---
layout: publication
title: DRDT Dynamic Reflection With Divergent Thinking For Llm45;based Sequential Recommendation
authors: Wang Yu, Liu Zhiwei, Zhang Jianguo, Yao Weiran, Heinecke Shelby, Yu Philip S.
conference: "Arxiv"
year: 2023
bibkey: wang2023dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11336"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
The rise of Large Language Models (LLMs) has sparked interest in their application to sequential recommendation tasks as they can provide supportive item information. However due to the inherent complexities of sequential recommendation such as sequential patterns across datasets noise within sequences and the temporal evolution of user preferences existing LLM reasoning strategies such as in45;context learning and chain45;of45;thought are not fully effective. To address these challenges we introduce a novel reasoning principle Dynamic Reflection with Divergent Thinking within a retriever45;reranker framework. Our approach starts with a collaborative in45;context demonstration retriever which collects sequences exhibiting collaborative behaviors as in45;context examples. Following this we abstract high45;level user preferences across multiple aspects providing a more nuanced understanding of user interests and circumventing the noise within the raw sequences. The cornerstone of our methodology is dynamic reflection a process that emulates human learning through probing critiquing and reflecting using user feedback to tailor the analysis more effectively to the target user in a temporal manner. We evaluate our approach on three datasets using six pre45;trained LLMs. The superior performance observed across these models demonstrates the efficacy of our reasoning strategy notably achieved without the need to fine45;tune the LLMs. With our principle we managed to outperform GPT45;Turbo45;3.5 on three datasets using 7b models e.g. Vicuna45;7b and Openchat45;7b on NDCG35;64;10. This research not only highlights the potential of LLMs in enhancing sequential recommendation systems but also underscores the importance of developing tailored reasoning strategies to fully harness their capabilities.
