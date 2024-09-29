---
layout: publication
title: Self45;instructed Derived Prompt Generation Meets In45;context Learning Unlocking New Potential Of Black45;box Llms
authors: Li Zhuo, Du Yuhao, Hu Jinpeng, Wan Xiang, Gao Anningzhe
conference: "Arxiv"
year: 2024
bibkey: li2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01552"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have shown success in generating high45;quality responses. In order to achieve better alignment with LLMs with human preference various works are proposed based on specific optimization process which however is not suitable to Black45;Box LLMs like GPT45;4 due to inaccessible parameters. In Black45;Box LLMs case their performance is highly dependent on the quality of the provided prompts. Existing methods to enhance response quality often involve a prompt refinement model yet these approaches potentially suffer from semantic inconsistencies between the refined and original prompts and typically overlook the relationship between them. To address these challenges we introduce a self45;instructed in45;context learning framework that empowers LLMs to deliver more effective responses by generating reliable derived prompts to construct informative contextual environments. Our approach incorporates a self45;instructed reinforcement learning mechanism enabling direct interaction with the response model during derived prompt generation for better alignment. We then formulate querying as an in45;context learning task using responses from LLMs combined with the derived prompts to establish a contextual demonstration for the original prompt. This strategy ensures alignment with the original query reduces discrepancies from refined prompts and maximizes the LLMs in45;context learning capability. Extensive experiments demonstrate that the proposed method not only generates more reliable derived prompts but also significantly enhances LLMs ability to deliver more effective responses including Black45;Box models such as GPT45;4.
