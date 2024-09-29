---
layout: publication
title: Refutebench: Evaluating Refuting Instruction-following For Large Language Models
authors: Yan Jianhao, Luo Yun, Zhang Yue
conference: "Arxiv"
year: 2024
bibkey: yan2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13463"}
tags: ['Applications', 'Prompting']
---
The application scope of large language models (LLMs) is increasingly expanding. In practical use users might provide feedback based on the models output hoping for a responsive model that can complete responses according to their feedback. Whether the model can appropriately respond to users refuting feedback and consistently follow through with execution has not been thoroughly analyzed. In light of this this paper proposes a comprehensive benchmark RefuteBench covering tasks such as question answering machine translation and email writing. The evaluation aims to assess whether models can positively accept feedback in form of refuting instructions and whether they can consistently adhere to user demands throughout the conversation. We conduct evaluations on numerous LLMs and find that LLMs are stubborn i.e. exhibit inclination to their internal knowledge often failing to comply with user feedback. Additionally as the length of the conversation increases models gradually forget the users stated feedback and roll back to their own responses. We further propose a recall-and-repeat prompts as a simple and effective way to enhance the models responsiveness to feedback.
