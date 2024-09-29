---
layout: publication
title: "oops, Did I Just Say That?" Testing And Repairing Unethical Suggestions Of Large Language Models With Suggest-critique-reflect Process
authors: Ma Pingchuan, Li Zongjie, Sun Ao, Wang Shuai
conference: "Arxiv"
year: 2023
bibkey: ma2023did
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.02626"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Responsible AI', 'Tools']
---
As the popularity of large language models (LLMs) soars across various applications ensuring their alignment with human values has become a paramount concern. In particular given that LLMs have great potential to serve as general-purpose AI assistants in daily life their subtly unethical suggestions become a serious and real concern. Tackling the challenge of automatically testing and repairing unethical suggestions is thus demanding. This paper introduces the first framework for testing and repairing unethical suggestions made by LLMs. We first propose ETHICSSUITE a test suite that presents complex contextualized and realistic moral scenarios to test LLMs. We then propose a novel suggest-critic-reflect (SCR) process serving as an automated test oracle to detect unethical suggestions. We recast deciding if LLMs yield unethical suggestions (a hard problem; often requiring human expertise and costly to decide) into a PCR task that can be automatically checked for violation. Moreover we propose a novel on-the-fly (OTF) repairing scheme that repairs unethical suggestions made by LLMs in real-time. The OTF scheme is applicable to LLMs in a black-box API setting with moderate cost. With ETHICSSUITE our study on seven popular LLMs (e.g. ChatGPT GPT-4) uncovers in total 109824 unethical suggestions. We apply our OTF scheme on two LLMs (Llama-13B and ChatGPT) which generates valid repair to a considerable amount of unethical ones paving the way for more ethically conscious LLMs.
