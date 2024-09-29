---
layout: publication
title: Verifiable By Design Aligning Language Models To Quote From Pre45;training Data
authors: Zhang Jingyu, Marone Marc, Li Tianjian, Van Durme Benjamin, Khashabi Daniel
conference: "Arxiv"
year: 2024
bibkey: zhang2024verifiable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03862"}
tags: ['RAG', 'Reinforcement Learning', 'Training Techniques']
---
To trust the fluent generations of large language models (LLMs) humans must be able to verify their correctness against trusted external sources. Recent efforts such as providing citations via retrieved documents or post45;hoc provenance enhance verifiability but still provide no guarantees on their correctness. To address these limitations we tackle the verifiability goal with a different philosophy trivializing the verification process by developing models that quote verbatim statements from trusted sources in pre45;training data. We propose Quote45;Tuning and demonstrate it is feasible to align LLMs to provide quoted statements from data memorized during pre45;training. The core of Quote45;Tuning is a fast membership inference function (Marone and Van Durme 2023) that efficiently verifies text against a trusted corpus. We leverage this tool to design a reward function to quantify quotes in model responses which is then used to create a dataset for preference learning. Experimental results show that Quote45;Tuning significantly increases verbatim quotes from high45;quality pre45;training documents by 5537; to 13037; relative to un45;tuned models while maintaining response quality. Quote45;Tuning also generalizes quoting to out45;of45;domain data is applicable in different tasks and provides additional benefits to truthfulness. Our method not only serves as a hassle45;free method to increase quoting but also opens up avenues for improving LLM trustworthiness through better verifiability.
