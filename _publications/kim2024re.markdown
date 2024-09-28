---
layout: publication
title: Re-Ex Revising after Explanation Reduces the Factual Errors in LLM Responses
authors: Kim Juyeon, Lee Jeongeun, Chang Yoonho, Choi Chanyeol, Kim Junseong, Sohn Jy-yong
conference: "Arxiv"
year: 2024
bibkey: kim2024re
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17097"}
tags: ['ARXIV', 'Interpretability', 'LLM', 'Prompt', 'Reinforcement Learning', 'Tools']
---
Mitigating hallucination issues is a key challenge that must be overcome to reliably deploy large language models (LLMs) in real-world scenarios. Recently various methods have been proposed to detect and revise factual errors in LLM-generated texts in order to reduce hallucination. In this paper we propose Re-Ex a method for post-editing LLM-generated responses. Re-Ex introduces a novel reasoning step dubbed as the factual error explanation step. Re-Ex revises the initial response of LLMs using 3-steps first external tools are used to retrieve the evidences of the factual errors in the initial LLM response; next LLM is instructed to explain the problematic parts of the response based on the gathered evidence; finally LLM revises the initial response using the explanations provided in the previous step. In addition to the explanation step Re-Ex also incorporates new prompting techniques to reduce the token count and inference time required for the response revision process. Compared with existing methods including FacTool CoVE and RARR Re-Ex provides better detection and revision performance with less inference time and fewer tokens in multiple benchmarks.
