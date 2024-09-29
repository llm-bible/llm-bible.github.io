---
layout: publication
title: Trojanrag Retrieval-augmented Generation Can Be Backdoor Driver In Large Language Models
authors: Cheng Pengzhou, Ding Yidong, Ju Tianjie, Wu Zongru, Du Wei, Yi Ping, Zhang Zhuosheng, Liu Gongshen
conference: "Arxiv"
year: 2024
bibkey: cheng2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13401"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Security', 'Survey Paper', 'Training Techniques']
---
Large language models (LLMs) have raised concerns about potential security threats despite performing significantly in Natural Language Processing (NLP). Backdoor attacks initially verified that LLM is doing substantial harm at all stages but the cost and robustness have been criticized. Attacking LLMs is inherently risky in security review while prohibitively expensive. Besides the continuous iteration of LLMs will degrade the robustness of backdoors. In this paper we propose TrojanRAG which employs a joint backdoor attack in the Retrieval-Augmented Generation thereby manipulating LLMs in universal attack scenarios. Specifically the adversary constructs elaborate target contexts and trigger sets. Multiple pairs of backdoor shortcuts are orthogonally optimized by contrastive learning thus constraining the triggering conditions to a parameter subspace to improve the matching. To improve the recall of the RAG for the target contexts we introduce a knowledge graph to construct structured data to achieve hard matching at a fine-grained level. Moreover we normalize the backdoor scenarios in LLMs to analyze the real harm caused by backdoors from both attackers and users perspectives and further verify whether the context is a favorable tool for jailbreaking models. Extensive experimental results on truthfulness language understanding and harmfulness show that TrojanRAG exhibits versatility threats while maintaining retrieval capabilities on normal queries.
