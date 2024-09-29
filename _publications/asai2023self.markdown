---
layout: publication
title: Self45;rag Learning To Retrieve Generate And Critique Through Self45;reflection
authors: Asai Akari, Wu Zeqiu, Wang Yizhong, Sil Avirup, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2023
bibkey: asai2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11511"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Tools']
---
Despite their remarkable capabilities large language models (LLMs) often produce responses containing factual inaccuracies due to their sole reliance on the parametric knowledge they encapsulate. Retrieval45;Augmented Generation (RAG) an ad hoc approach that augments LMs with retrieval of relevant knowledge decreases such issues. However indiscriminately retrieving and incorporating a fixed number of retrieved passages regardless of whether retrieval is necessary or passages are relevant diminishes LM versatility or can lead to unhelpful response generation. We introduce a new framework called Self45;Reflective Retrieval45;Augmented Generation (Self45;RAG) that enhances an LMs quality and factuality through retrieval and self45;reflection. Our framework trains a single arbitrary LM that adaptively retrieves passages on45;demand and generates and reflects on retrieved passages and its own generations using special tokens called reflection tokens. Generating reflection tokens makes the LM controllable during the inference phase enabling it to tailor its behavior to diverse task requirements. Experiments show that Self45;RAG (7B and 13B parameters) significantly outperforms state45;of45;the45;art LLMs and retrieval45;augmented models on a diverse set of tasks. Specifically Self45;RAG outperforms ChatGPT and retrieval45;augmented Llama245;chat on Open45;domain QA reasoning and fact verification tasks and it shows significant gains in improving factuality and citation accuracy for long45;form generations relative to these models.
