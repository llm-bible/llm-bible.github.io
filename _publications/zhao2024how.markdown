---
layout: publication
title: 'How Do Large Language Models Handle Multilingualism?'
authors: Zhao Yiran, Zhang Wenxuan, Chen Guizhen, Kawaguchi Kenji, Bing Lidong
conference: "Arxiv"
year: 2024
bibkey: zhao2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18815"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) have demonstrated impressive capabilities across diverse languages. This study explores how LLMs handle multilingualism. Based on observed language ratio shifts among layers and the relationships between network structures and certain capabilities we hypothesize the LLMs multilingual workflow (()) LLMs initially understand the query converting multilingual inputs into English for task-solving. In the intermediate layers they employ English for thinking and incorporate multilingual knowledge with self-attention and feed-forward structures respectively. In the final layers LLMs generate responses aligned with the original language of the query. To verify () we introduce Parallel Language-specific Neuron Detection (()) to identify activated neurons for inputs in different languages without any labeled data. Using () we validate () through extensive experiments involving the deactivation of language-specific neurons across various layers and structures. Moreover () allows fine-tuning of language-specific neurons with a small dataset enhancing multilingual abilities in a specific language without compromising others. This approach results in an average improvement of (3.6) for high-resource languages and (2.3) for low-resource languages across all tasks with just (400) documents.
