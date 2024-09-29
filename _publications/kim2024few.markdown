---
layout: publication
title: "Few-shot Personalization Of Llms With Mis-aligned Responses"
authors: Kim Jaehyung, Yang Yiming
conference: "Arxiv"
year: 2024
bibkey: kim2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18678"}
tags: ['Few Shot', 'Pretraining Methods', 'Prompting', 'RAG']
---
As the diversity of users increases the capability of providing personalized responses by large language models (LLMs) has become increasingly important. Existing approaches have only limited successes in LLM personalization due to the absence of personalized learning or the reliance on shared personal data. This paper proposes a new approach for a few-shot personalization of LLMs with their mis-aligned responses (Fermi). Our key idea is to learn a set of personalized prompts for each user by progressively improving the prompts using LLMs based on user profile (e.g. demographic information) and a few examples of previous opinions. During an iterative process of prompt improvement we incorporate the contexts of mis-aligned responses by LLMs which are especially crucial for the effective personalization of LLMs. In addition we develop an effective inference method to further leverage the context of the test query and the personalized prompts. Our experimental results demonstrate that Fermi significantly improves performance across various benchmarks compared to the best-performing baselines.
