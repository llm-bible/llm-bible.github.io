---
layout: publication
title: How Do Large Language Models Handle Multilingualism
authors: Zhao Yiran, Zhang Wenxuan, Chen Guizhen, Kawaguchi Kenji, Bing Lidong
conference: "Arxiv"
year: 2024
bibkey: zhao2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18815"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated impressive capabilities across diverse languages. This study explores how LLMs handle multilingualism. Based on observed language ratio shifts among layers and the relationships between network structures and certain capabilities we hypothesize the LLMs multilingual workflow (texttt123;MWork125;) LLMs initially understand the query converting multilingual inputs into English for task45;solving. In the intermediate layers they employ English for thinking and incorporate multilingual knowledge with self45;attention and feed45;forward structures respectively. In the final layers LLMs generate responses aligned with the original language of the query. To verify texttt123;MWork125; we introduce Parallel Language45;specific Neuron Detection (texttt123;PLND125;) to identify activated neurons for inputs in different languages without any labeled data. Using texttt123;PLND125; we validate texttt123;MWork125; through extensive experiments involving the deactivation of language45;specific neurons across various layers and structures. Moreover texttt123;MWork125; allows fine45;tuning of language45;specific neurons with a small dataset enhancing multilingual abilities in a specific language without compromising others. This approach results in an average improvement of 3.637; for high45;resource languages and 2.337; for low45;resource languages across all tasks with just 400 documents.
