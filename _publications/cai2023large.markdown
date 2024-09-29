---
layout: publication
title: Large Language Models As Tool Makers
authors: Cai Tianle, Wang Xuezhi, Ma Tengyu, Chen Xinyun, Zhou Denny
conference: "Arxiv"
year: 2023
bibkey: cai2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17126"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Tools']
---
Recent research has highlighted the potential of large language models (LLMs) to improve their problem45;solving capabilities with the aid of suitable external tools. In our work we further advance this concept by introducing a closed45;loop framework referred to as LLMs A s Tool Makers (LATM) where LLMs create their own reusable tools for problem45;solving. Our approach consists of two phases 1) tool making an LLM acts as the tool maker that crafts tools for a set of tasks. 2) tool using another LLM acts as the tool user which applies the tool built by the tool maker for problem45;solving. On the problem45;solving server side tool45;making enables continual tool generation and caching as new requests emerge. This framework enables subsequent requests to access cached tools via their corresponding APIs enhancing the efficiency of task resolution. Recognizing that tool45;making requires more sophisticated capabilities we assign this task to a powerful albeit resource45;intensive model. Conversely the simpler tool45;using phase is delegated to a lightweight model. This strategic division of labor allows the once45;off cost of tool45;making to be spread over multiple instances of tool45;using significantly reducing average costs while maintaining strong performance. Furthermore our method offers a functional cache through the caching and reuse of tools which stores the functionality of a class of requests instead of the natural language responses from LLMs thus extending the applicability of the conventional cache mechanism. We evaluate our approach across various complex reasoning tasks including Big45;Bench tasks. With GPT45;4 as the tool maker and GPT45;3.5 as the tool user LATM demonstrates performance equivalent to using GPT45;4 for both roles but with a significantly reduced inference cost.
