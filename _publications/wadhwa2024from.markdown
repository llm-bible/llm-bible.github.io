---
layout: publication
title: 'From Rags To Rich Parameters: Probing How Language Models Utilize External Knowledge Over Parametric Information For Factual Queries'
authors: Wadhwa Hitesh, Seetharaman Rahul, Aggarwal Somyaa, Ghosh Reshmi, Basu Samyadeep, Srinivasan Soundararajan, Zhao Wenlong, Chaudhari Shreyas, Aghazadeh Ehsan
conference: "Arxiv"
year: 2024
bibkey: wadhwa2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12824"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
"Retrieval Augmented Generation (RAG) enriches the ability of language models to reason using external context to augment responses for a given user prompt. This approach has risen in popularity due to practical applications in various applications of language models in search, question/answering, and chat-bots. However, the exact nature of how this approach works isn't clearly understood. In this paper, we mechanistically examine the RAG pipeline to highlight that language models take shortcut and have a strong bias towards utilizing only the context information to answer the question, while relying minimally on their parametric memory. We probe this mechanistic behavior in language models with: (i) Causal Mediation Analysis to show that the parametric memory is minimally utilized when answering a question and (ii) Attention Contributions and Knockouts to show that the last token residual stream do not get enriched from the subject token in the question, but gets enriched from other informative tokens in the context. We find this pronounced shortcut behaviour true across both LLaMa and Phi family of models."
